# voice-amu-waldek-hsmm

A male Polish hidden semi-Markov model voice, built from voice recordings provided by the [Department of Phonetics](http://www.staff.amu.edu.pl/~fonetyka/) at [AMU Poznań](https://international.amu.edu.pl/)

## Prerequisites

You will need to have [Java](https://www.java.com/) installed.
On OSX with [Homebrew](http://brew.sh/), do
```
$ brew cask install java
```
as needed.

On Debian-based Linux (including Ubuntu), do
```
$ sudo apt-get install default-jdk
```
accordingly.

### Building the voice

To assemble, test, and package the voice, do
```
$ ./gradlew build
```

### Running the voice

To build the voice and run it in an ad-hoc MaryTTS server, do
```
$ ./gradlew run
```
Then, go to [http://localhost:59125](http://localhost:59125/).
