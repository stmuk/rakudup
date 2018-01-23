# rakudup

"Don't pipe that curl download to a shell, it could do something dangerous.
Instead, download the source archive and then blindly execute the 300Kb of
obfuscated shell script as './configure' -- Joshua Stein

So go on

curl https://raw.githubusercontent.com/stmuk/rakudup/master/rakudup | bash
