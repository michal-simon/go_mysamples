# go_mysamples

[![Codeac.io](https://static.codeac.io/badges/2-142351717.svg)](https://app.codeac.io/github/aeciopires/go_mysamples)

[English]: #english
[Contributing]: #contributing
[Developers]: #developers
[Tutorials]: #tutorials
[License]: #license

#### Menu

1. [English][English]
2. [Contributing][Contributing]
3. [Developers][Developers]
4. [Tutorials][Tutorials]
5. [License][License]

# English

My samples of binaries developed with go language.

* `src`: contains the source code, as well as the source code of third party packages imported into our programs;
* `pkg`: contains objects related to packages;
* `bin`: contains executable files generated by the programs we compiled.

## Contributing

1. Install packages: `git`, `go`, `curl`. Or use Go in Docker: https://hub.docker.com/_/golang
2. Clone the repository to your machine through the command: `git clone https://github.com/aeciopires/go_mysamples`
3. Go to the project folder: `cd go_mysamples`
4. Create a branch using the pattern: `git checkout -b US-${DEV_NAME}`. Example: *git checkout -b US-AECIO*
5. Develop the task
6. Execute the code in 'development' and 'test' environments
7. Do commit and push files to repository remote with command `git push --set-upstream origin US-${DEV_NAME}`. Example: *git push --set-upstream origin US-AECIO*
8. Create Pull Request (PR) to the `master` branch, using the notations patterns of the development process
9. Update the content with the suggestions of the reviewer (if necessary)

**WARNING:** Before start to contribute, run the command: `git pull origin master` to fetch the newest content of the main branch and avoid conflicts that can make you waste time.

## Developers

developer: Aécio dos Santos Pires<br>
mail: http://blog.aeciopires.com/contato

## Tutorials

Use Go in Docker: https://hub.docker.com/_/golang

```
git clone https://github.com/aeciopires/go_mysamples

cd go_mysamples/src

VERSION=1.13.5-alpine

docker run --rm -v "$PWD":/usr/src/myapp -w /usr/src/myapp golang:$VERSION go build -v

./myapp
```

This will add your current directory as a volume to the container, set the working directory to the volume, and run the command go build which will tell go to compile the project in the working directory and output the executable to myapp.

Or

Install go from source:

```
VERSION=1.13.5

curl https://dl.google.com/go/go$VERSION.linux-amd64.tar.gz -o go.tar.gz

sudo tar -C /usr/local -xzf go.tar.gz

export PATH=$PATH:/usr/local/go/bin

go version
```

Executing programs with go. Exemple:

```
git clone https://github.com/aeciopires/go_mysamples

cd go_mysamples/src

go run helloword.go
```

Tutorials and documentation about go language:

* https://medium.com/@denis_santos/primeiros-passos-com-golang-c3368f6d707a
* https://tour.golang.org
* https://www.youtube.com/watch?v=YS4e4q9oBaU
* https://www.youtube.com/watch?v=Q0sKAMal4WQ
* https://www.youtube.com/watch?v=G3PvTWRIhZA
* https://stackify.com/learn-go-tutorials/
* https://golangbot.com/
* https://www.tutorialspoint.com/go/index.htm
* https://www.guru99.com/google-go-tutorial.html
* http://www.golangbr.org/doc/codigo
* https://golang.org/doc/articles/wiki/
* https://gobyexample.com/
* https://hackr.io/tutorials/learn-golang
* https://hackernoon.com/basics-of-golang-for-beginners-6bd9b40d79ae
* https://medium.com/hackr-io/learn-golang-best-go-tutorials-for-beginners-deb6cab45867


## License

GPL-3.0 2020 Aécio dos Santos Pires


