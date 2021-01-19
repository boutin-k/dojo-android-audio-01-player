# Lecteur Audio

## But du TD
Faire un lecteur audio qui diffusera la musique suivante en streaming :
* http://images.innoveduc.fr/android/Green%20Day%20-%20Revolution.mp3

## Etapes
Faire un layout contenant 3 boutons : 
* Play > Lance la lecture du media
* Pause > Mets en pause la lecture du media.
* Reset > Repositionne la lecture du media au départ du média.

> Attention :
> Le lecteur doit être initialisé avec prepareAsync()
> La permission INTERNET doit être ajoutée dans le fichier AndroidManifest.xml

Bonus : 
Lorque la chanson est finie elle redémarre (effet loop).
Ajouter un checkbox pour activer/désactiver l’effet loop.
Ajouter une seekBar permettant de se déplacer dans la chanson.

## Documentation :
* [MediaPlayer overview](https://developer.android.com/guide/topics/media/mediaplayer)
* [MediaPlayer class](https://developer.android.com/reference/android/media/MediaPlayer)
* [Media app architecture overview](https://developer.android.com/guide/topics/media-apps/media-apps-overview)


## TD suivant :
* [Audio Manager](https://github.com/boutin-k/dojo-android-audio-02-manager)
