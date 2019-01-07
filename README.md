# Systemy Operacyjne

# LAB1
* Wprowadzenie, konfiguracja IDE, kompilacja
  - Flagi: Werror, Wall, pedantic, std=c++11
* Pierwszy program, uruchamianie programów wsystemie Win32, punkt wejścia, przekazywanie
argumentów
  - int _tmain(int argv, TCHAR *argv[], TCHAR *envp[]);
  - int main(int argc, char** argv)
* Wprowadzenie do obsługi plików
  - CreateFile, WriteFile, typ HANDLE
  
# LAB2
* Obsługa plików za pomocą API Win32
	- CreateFile, WriteFile, ReadFile, GetFileSize
* Parametry funkcji CreateFile
	- dwDesiredAccess,
	– dwShareMode,
	– lpSecurityAttributes,
	– dwCreationDisposition
* Porządkowanie kodu, refatkoryzacja, podział na funkcje, klasy, camelCase, linux_case, notacja węgierska
