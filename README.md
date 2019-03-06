# RTR108
Studiju kursa Datormācība (speckurss) elektroniskā klade
## Kā izmantot git upload
1.git clone https://github.com/JanaNiedrite/RTR108
2.mv nosk.ko.ievietot RTR108/
3.cd RTR108
4../git.upload datums_laiks
## 2.nodarbības pieraksti 
1.rinda 
2.rinda   
3.rinda  
## 4.nodarbība
1.Lai uzzinātu,kur atrodies - pwd 
2.Lai uzzinātu,kas es esmu - whoami 
3.Kas vēl strādā - who 
4.Kāda ir OS sistēma - uname 
4.1. paplašinātāk -  uname -a
5.Shell dialekts ar kādu strādā OS - echo %0
5.chmod - lai nomainītu, to ko var darīt ar failu
## 5.nodarbība
1.Read only variables - ja funkcija ir piešķirts read only, tad tā vērtību nevar mainīt
2.Unsetting variables - Unsetting or deleting a variable directs the shell to remove the variable from the list of variables that it tracks. Once you unset a variable, you cannot access the stored value in the variable.
2.Comand-Line Arguments - $1,$2,..,$9 ir command-line arguments parametri, kas seko komandai, shell skriptam, utt.
3.Special Parametrs - allow accessing all the command-line arguments at once. $* and $@ both will act the same unless they are enclosed in double quotes, "".
4.Exit Status - $?
5.Defining Array Values + Accesing Array Values - katram masīvam tiek piešķirts indekss, lai tā ievadīto sastāvu varētu atrast pēc indekss, pievienojot kodam echo un masīvu+indeksu, tas tiks izvadīts uz ekrāna
6.Arithmetic operators - aritmētiskās operācijas shell valodā - jāpieraksta [] un darbībām jābūt ar atstarpēm.
7.Nesting loop - vienu loop var ielikt citā loop
8.Infinit loop -  A loop that executes forever without terminating executes for an infinite number of times. For this reason, such loops are called infinite loops.
9.The break statement - apstādina loop un atastāj/uzrāda vērtības/intervālu, kas ierakstīt koda
10.The continue statement - var pielietot uzrādot kādu kļūdu programmā, piemēram, ja nepieciešams atrast nepāra skaitli starp pāra skaitļiem.
11.Substitution - vairākas funkcijas, kas ietver pēc ievadītā satura kādu funkciju, piemēram, "\n" izveido atstarpi.
12.Command substitution - Command substitution is the mechanism by which the shell performs a given set of commands and then substitutes their output in the place of the commands.
13.Variable substitution - enables the shell programmer to manipulate the value of a variable based on its state.
