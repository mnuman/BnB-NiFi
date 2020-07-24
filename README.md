# BnB-NiFi
Deze repository is de repository voor het materiaal voor de SynTouch Bits & Bites over Apache NiFi. De repository bevat materialen zoals:
- build script voor het docker image
- instructies/tutorials

## Docker image bouwen
1. open een shell (powershell/Git Bash) en ga hierin naar de directory waarin de Dockerfile zich bevindt
1. voer het volgende commando uit om het image te bouwen:

```docker build -t <your_desired_image_name>:<optional_image_tag> .```

## Uitvoeren van het docker image

```docker run -d --name nifi -p 8080:8080 -p 8090:8090 <your_desired_image_name>:<optional_image_tag>```