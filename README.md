# VeNuS
Hackmyvm challenges

*SOPHIAS'S PASSWORD *Y1o645M3mR84ejc*

    Use of CAT to read files.

*ANGELA'S PASSWORD *oh5p9gAABugHBje**

    Use *FIND* command to search for files {find / -type f -name "whereismypazz.txt" 2>/dev/nul}.
    - find - search.
    -/ - search in the root directory.
    - -type f - search for files.
    - -name "whereismypazz.txt" - name of the file.
    - 2>/dev/null - direct all and discards any data written to it while reporting that the operation was successful.

EMMA'S PASSWORD *fIvltaGaq0OUH8O*

    Using *SED* to find txt within lines inside a large file {sed -n "4069p" findme.txt}.
    - sed - is a Stream Editor (does line by line processing).
    - -n - sed will print the line automatically if told to do so.
      **NB:without -n file is dumped out (all is printed out)**.
    - '4069p'-print line no.4069.
    - findme.txt - file being read.

*MIA'S PASSWORD *iKXIYg0pyEH2Hos**

    Redirection- most of the time Linux uses (-) as stdin or stdout instead of a filename.
      Use ./- to inform the system that (-) is a filename 
    
    - . indicating that its in the current directory.
    - / to indicate the path.

*CAMILA'S PASSWORD *F67aDmCAAgOOaOc**

    Searching information within files in directories.
      Use *FIND* to find the directory {find / -type d -name "hereiam" 2>/dev/null}
    
    - -type d - search for directories.
    - -name "hereiam" - directory name
      cd to /opt/hereiam
        then cat {/opt/hereiam/.here}

  *LUNA'S PASSWORD *j3vkuoKQwvbhkMc**

      Searching insidde folders
        Use *FIND* to find the file in the current directory {find . -type f 2>/dev/  null}
  
      cd to muack
        cat it or ls / cat ./111/111/muack

*ELEANOR'S PASSWORD *UNDchvln6Bmtu7b**

    Find by size using *FIND* {find / -type f -size 6969c 2>/dev/null}

    - -size 6969c - 69696c bytes.
    - / search the whole Luna system.
    - -type f - search for only files.
    cat /usr/share/moon.txt

*VICTORIA'S PASSWORD *pz8OqvJBFxH0cSj**

    Searching files in another users file system.
      Find the different user using {find / -type f -user "violin" 2>/dev/null}
    -  -user "violin" - search for the files owned by user violin.
       cat /usr/local/games/yo

*ISLA;S PASSWORD *D3XTob0FUImsoBb**

    Unzipping files
      Use {unzip -o passw0rd.zip -d /tmp} to create a temporary file and unzip it.
        - -o - to prevent overwriting the file.
        - -d - for extraction.
        - /tmp - to create a temporary file.
        cat /tmp/pwned/victoria/passw0rd.txt

*VIOLET'S PASSWORD *WKINVzNQLKLDVAc**

    Use of *GREP*
    Use {grep "^a9HFX" passy}
    Another alternative is using (sed -n 's/^a9HFX//p' passy)
    where; s/^a9HFX// - is for removing the prefix #a9HFX
          p - for print result

*LUCY'S PASSWORD *OCmMUjebG53giud**

    Use of *GREP* and *SED* {grep "0JuAZ$" end | sed 's/0JuAZ$//'}
    GREP- searches for a the line
    SED- pinpoints the details of the start and end of the line
    
    **grep "0JuAZ$"**
    - $ means “end of line”
    -finds lines ending with 0JuAZ
    -sed 's/0JuAZ$//'
    -removes 0JuAZ from the end
    
    ANother alternative is using only SED {sed -n 's/0JuAZ$//p' filename}

  *ELENA'S PASSWORD *4xZ5lIKYmfPLg9t**

    Use GREP {grep -oP '(?<=fu).*(?=ck)' file.yo}
      (?<=fu)
      - positive lookbehind and “start after fu”
      .* - grab everything
      (?=ck)
      - positive lookahead and “stop before ck”
  
*alice**Cgecy2MY2MWbaqt**
*anna**w8NvY27qkpdePox**
*natalia**NMuc4DkYKDsmZ5z**
eva/upsCA3UFu10fDAO
clara/39YziWp5gSvgQN9
frida/Ed4ErEUJEaMcXli
eliza/Fg6b6aoksceQqB9
iris/kYjyoLcnBZ9EJd
eloise/yOUJlV0SHOnbSPm
lucia/uvMwFDQrQWPMeGP
isabel/H5ol8Z2mrRsorC0                        2jA0E8bQ4WrGwWZ
freya/EEDyYFDwYsmYawj
alexa/mxq9O3MSxxX9Q3S
ariel/33EtHoz9a0w2Yqo
lola/d3LieOzRGX5wud6
celeste/VLSNMTKwSV2o8Tn

nina/ixpeqdWuvC5N9kG

mysql -u celeste -p
    MariaDB [(none)]> SHOW DATABASES;
    mysqldump -u celeste -p venus > /tmp/dump.sql
mysqldump --skip-lock-tables -u celeste -p venus > /tmp/dump.sql
cat /tmp/dump.sql
rep "^(" /tmp/dump.sql | cut -d"'" -f2 | grep -Fxf <(cut -d: -f1 /etc/passwd)

kira/tPlqxSKuT4eP3yr

curl -X PUT http://localhost/method.php

veronica/QTOel6BodTx2cwX

curl -A "PARADISE" http://localhost/waiting.php

lana/UWbc0zNEVVops1v

alias | grep lana

Noa/9WWOPoeJrq6ncvJ

cd /dev/shm
mkdir extract
cp /pwned/lana/zip.gz ./archive.tar
tar --strip-components=2 -xf archive.tar -C extract
find extract
cd extract
ls -la
cat zip

maia/h1hnDPHpydEjoEN

strings trash | grep -i DPH OR strings -n 10 trash
OUTPUT= \nh1hnDPHpydEjoEN
\n is just binary data

