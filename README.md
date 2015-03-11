1. Środowisko
  - 15 min  - Tooling czyli co do czego z samego Go
      - instalacja
      - GOPATH oraz dodanie GOPATH/bin do PATH
  - 45 min  - IDE https://github.com/golang/go/wiki/IDEsAndTextEditorPlugins
  - przerwa
2. Wstęp do GoLang
  - Tutaj zapytałbym ludzi jaki jest ich poziom i czego by się chcieli nauczyć... jeśli wiekszość powie że nie wiele, to tak bym postąpił dalej.
  - 20 min
    - zasady tworzenia pakietów

        $ mkdir -p $GOPATH/src/github.com/user
        $ mkdir $GOPATH/src/github.com/user/hello
        $ vim $GOPATH/src/github.com/user/hello/main.go
        
    and content
        
        import "fmt"
        
        func main() {
        	fmt.Printf("Hello, world.\n")
        }



    - jak tworzyć projekt
    - ...
3. Kodzimy (wg http://golang.org.pl)
  - zabawa z kodem czyli w sumie fmt, wskaźniki, dlaczego nie ma tablic itp.
  - przykład i jazda, przyklad i jazda

Za inspiracje do poznaniwa go użyłbym po prostu http://golang.org.pl/ bo:
  - Jest dość aktalne
  - Kto nie zdąży, skończy w domu.
