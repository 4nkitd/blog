# golang for everything

`not recommended`

I have made a few of projects with golang from a simple website to a (dead)microservice/lambda-function/edge-server.

i try to explain what i like about this language & why. Also weather you should consider it as an option for you. in other words i'll try to sell golang to you. let's see if it works.

## Top Selling Points

- Development Tools
- Operated Architecture with Optional Implementation
- Multi Platform Support
- Package manager
- Other tings people say but i have never tried.

### Development Tools

I use vs-code for my day-today tasks and i love that google themselves has build the tooling for that by themselves and have not to rely on a third party to implement things like auto-completion, syntax highlighting, etc. Also it's not mandatory to use vs code they provide the tooling as cli tool which you can use regardless for thr code-editor/ide you use.

### Operated Architecture with Optional Implementation

Their have been multiple tries by many organizations/individual's to standardize the coding styles. but each time it idea/concept was implemented at framework level or through a third party tool. golang has a built in tool called `gofmt` which is a tool that formats the code according to the standard. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `goimports` which is a tool that formats the code according to the standard and also adds the import statements for you. So you don't have to worry about the import statements. `THIS IS THE BIG REASON THAT WHENEVER YOU SEE A GOLANG CODE IT LOOKS THE SAME` NO MATTER WHO WROTE IT.

### Multi Platform Support

i have not read documentation but i have seen people using golang to build applications for windows, linux, mac, android, ios, etc. so it's a good option if you want to build a cross platform application. i also tried web-assembly with `tinygo` that can slo be a good option.

### Package manager

have worked with php, js/nodejs, java, ruby and other industry standard languages. but i have never seen a package manager that is as good as `go get` it's a tool that can be used to download the packages from the internet and also to update the packages. it's also a good practice to use `go mod` which is a tool that manages the dependencies for you. it's not mandatory to use it but it's a good practice to use it. it is a lot similar to `DENO` iy you have seen that. i'm not familiar with the creator of `DENO` but to me it seem like a lot of things in `DENO` are inspired by golang. 

### Other tings people say but i have never tried.

1. Concurrency
2. Performance
3. etc.

#### Concurrency

golang has a built in tool called `goroutines` which is a tool that can be used to run multiple tasks at the same time. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `channels` which is a tool that can be used to communicate between the goroutines. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `sync` which is a tool that can be used to synchronize the goroutines. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `waitgroups` which is a tool that can be used to wait for the goroutines to finish. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `mutex` which is a tool that can be used to synchronize the goroutines. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `atomic` which is a tool that can be used to synchronize the goroutines. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `context` which is a tool that can be used to synchronize the goroutines. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `select` which is a tool that can be used to synchronize the goroutines. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `defer` which is a tool that can be used to synchronize the goroutines. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `panic` which is a tool that can be used to synchronize the goroutines. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `recover` which is a tool that can be used to synchronize the goroutines. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `go vet` which is a tool that can be used to synchronize the goroutines. it's not mandatory to

#### Performance

golang has a built in tool called `go build` which is a tool that can be used to build the application. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `go run` which is a tool that can be used to run the application. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `go test` which is a tool that can be used to test the application. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `go fmt` which is a tool that can be used to format the application. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `go vet` which is a tool that can be used to vet the application. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `go doc` which is a tool that can be used to document the application. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `go get` which is a tool that can be used to get the application. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `go install` which is a tool that can be used to install the application. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `go mod` which is a tool that can be used to mod the application. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `go clean` which is a tool that can be used to clean the application. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `go list` which is a tool that can be used to list the application. it's not mandatory to use it but it's a good practice to use it. it's also a good practice to use `go env` which is a tool that can be used to env the application. it's not mandatory to use it but it's a good

### Conclusion

if you need/want a programing language and don't want to get too close to the kernel or in other words you have to use c/c++/cs/rust but you don't want to use it, go for golang.
