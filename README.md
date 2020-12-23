# setopts

A good set of base ZSH options

## Options

```zsh
$ set -o
noaliases             off
aliasfuncdef          off
allexport             off
noalwayslastprompt    off
alwaystoend           on
appendcreate          off
noappendhistory       off
autocd                on
autocontinue          off
noautolist            off
noautomenu            off
autonamedirs          off
noautoparamkeys       off
noautoparamslash      off
autopushd             on
noautoremoveslash     off
autoresume            on
nobadpattern          off
nobanghist            off
nobareglobqual        off
bashautolist          off
bashrematch           off
nobeep                on
nobgnice              on
braceccl              off
bsdecho               off
nocaseglob            off
nocasematch           off
cbases                off
cdablevars            off
cdsilent              off
chasedots             off
chaselinks            off
nocheckjobs           on
nocheckrunningjobs    off
noclobber             on
combiningchars        on
completealiases       off
completeinword        on
continueonerror       off
correct               off
correctall            off
cprecedences          off
cshjunkiehistory      off
cshjunkieloops        off
cshjunkiequotes       off
cshnullcmd            off
cshnullglob           off
nodebugbeforecmd      off
dvorak                off
emacs                 on
noequals              off
errexit               off
errreturn             off
noevallineno          off
noexec                off
extendedglob          on
extendedhistory       off
noflowcontrol         on
forcefloat            off
nofunctionargzero     off
noglob                off
noglobalexport        off
noglobalrcs           off
globassign            off
globcomplete          off
globdots              on
globstarshort         off
globsubst             off
nohashcmds            off
nohashdirs            off
hashexecutablesonly   off
nohashlistall         off
histallowclobber      off
nohistbeep            off
histexpiredupsfirst   off
histfcntllock         off
histfindnodups        off
histignorealldups     off
histignoredups        off
histignorespace       off
histlexwords          off
histnofunctions       off
histnostore           off
histreduceblanks      off
nohistsavebycopy      off
histsavenodups        off
histsubstpattern      off
histverify            off
nohup                 on
ignorebraces          off
ignoreclosebraces     off
ignoreeof             off
incappendhistory      off
incappendhistorytime  off
interactive           on
interactivecomments   on
ksharrays             off
kshautoload           off
kshglob               off
kshoptionprint        off
kshtypeset            off
kshzerosubscript      off
nolistambiguous       off
nolistbeep            off
listpacked            off
listrowsfirst         off
nolisttypes           off
localloops            off
localoptions          off
localpatterns         off
localtraps            off
login                 off
longlistjobs          on
magicequalsubst       off
mailwarning           off
markdirs              off
menucomplete          off
monitor               on
nomultibyte           off
nomultifuncdef        off
nomultios             off
nonomatch             off
nonotify              off
nullglob              off
numericglobsort       off
octalzeroes           off
overstrike            off
pathdirs              on
pathscript            off
pipefail              off
posixaliases          off
posixargzero          off
posixbuiltins         off
posixcd               off
posixidentifiers      off
posixjobs             off
posixstrings          off
posixtraps            off
printeightbit         off
printexitvalue        off
privileged            off
promptbang            off
nopromptcr            off
nopromptpercent       off
nopromptsp            off
promptsubst           on
pushdignoredups       on
pushdminus            on
pushdsilent           off
pushdtohome           off
rcexpandparam         off
rcquotes              on
norcs                 off
recexact              off
rematchpcre           off
restricted            off
rmstarsilent          off
rmstarwait            off
sharehistory          off
shfileexpansion       off
shglob                off
shinstdin             on
shnullcmd             off
shoptionletters       off
noshortloops          off
shwordsplit           off
singlecommand         off
singlelinezle         off
sourcetrace           off
sunkeyboardhack       off
transientrprompt      off
trapsasync            off
typesetsilent         off
nounset               off
verbose               off
vi                    off
warncreateglobal      off
warnnestedvar         off
xtrace                off
zle                   on
```

## Installation

- [znap]: `znap clone mattmc3/zsh-setopts && znap source zsh-setopts`
- [antibody]: `antibody bundle mattmc3/zsh-setopts`
- [zgen]: `zgen load mattmc3/zsh-setopts`
- [antigen]: `antigen bundle mattmc3/zsh-setopts`

[antigen]: https://github.com/zsh-users/antigen
[antibody]: https://getantibody.github.io
[znap]: https://github.com/marlonrichert/zsh-snap
[zgen]: https://github.com/tarjoilija/zgen
