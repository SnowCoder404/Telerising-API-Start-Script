# Telerising-API-Start-Script


Ein init.d Script zum Starten und Stopen von Telerising-API.


Zum instaliren :

wget https://github.com/sunsettrack4/telerising-api/blob/main/telerising-v0.10.9_x86-64_linux.zip
cpan install DateTime::Format::Strptime
cpan install  JSON;
cpan install  JSON::Parse 
cpan install  HTTP::Request ();
cpan install  LWP::UserAgent;
cpan install  URI::Escape;
cpan install  UUID::Tiny 
cpan install  Cwd qw(cwd);
cpan install  File::Which;

Die Zip Datei müssen sie entpacken und alles nach /opt kopiren.
Danach chmod +x /opt/telerising-api/api 
