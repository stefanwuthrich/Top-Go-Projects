# Go Frameworks

- [Go Frameworks](#go-frameworks)
  - [Command Line](#command-line)
  - [Console UI](#console-ui)
    - [Console UI Engine/Library](#console-ui-enginelibrary)
  - [Web Frameworks](#web-frameworks)
  - [Game](#game)
    - [Game engine](#game-engine)

## Command Line

|                        Repo                        |               &nbsp;&nbsp;&nbsp;&nbsp;Stars&nbsp;&nbsp;&nbsp;&nbsp;                |                          &nbsp;&nbsp;&nbsp;&nbsp;Forks&nbsp;&nbsp;&nbsp;&nbsp;                          |                                                              Description                                                               |
| -------------------------------------------------- | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| [cobra](https://github.com/spf13/cobra)            | ![stars](http://githubbadges.com/star.svg?user=spf13&repo=cobra&style=flat)        | ![forks](http://githubbadges.com/fork.svg?user=spf13&repo=cobra&style=flat&color=fff&background=1282C2) | Cobra is both a library for creating powerful modern CLI applications as well as a program to generate applications and command files. |
| [urfave/cli](https://github.com/urfave/cli)        | ![stars](http://githubbadges.com/star.svg?user=urfave&repo=cli&style=flat)         | ![forks](https://img.shields.io/github/forks/urfave/cli.svg)                                            | A simple, fast, and fun package for building command line apps in Go.                                                                  |
| [kingpin](https://github.com/alecthomas/kingpin)   | ![stars](http://githubbadges.com/star.svg?user=alecthomas&repo=kingpin&style=flat) | ![forks](https://img.shields.io/github/forks/alecthomas/kingpin.svg)                                    | A Go (golang) command line and flag parser                                                                                             |
| [go-flags](https://github.com/jessevdk/go-flags)   | ![stars](http://githubbadges.com/star.svg?user=jessevdk&repo=go-flags&style=flat)  | ![forks](https://img.shields.io/github/forks/jessevdk/go-flags.svg)                                     | A go library for parsing command line arguments                                                                                        |
| [docopt](https://github.com/docopt/docopt.go)      | ![stars](http://githubbadges.com/star.svg?user=docopt&repo=docopt.go&style=flat)   | ![forks](https://img.shields.io/github/forks/docopt/docopt.go.svg)                                      | Helps creating beautiful command-line interfaces easily.                                                                               |
| [readline](https://github.com/chzyer/readline)     | ![stars](http://githubbadges.com/star.svg?user=chzyer&repo=readline&style=flat)    | ![forks](https://img.shields.io/github/forks/chzyer/readline.svg)                                       | Readline is a pure go(golang) implementation for GNU-Readline kind library.                                                            |
| [mitchellh/cli](https://github.com/mitchellh/cli)  | ![stars](http://githubbadges.com/star.svg?user=mitchellh&repo=cli&style=flat)      | ![forks](https://img.shields.io/github/forks/mitchellh/cli.svg)                                         | A Go library for implementing command-line interfaces.                                                                                 |
| [go-arg](https://github.com/alexflint/go-arg)      | ![stars](http://githubbadges.com/star.svg?user=alexflint&repo=go-arg&style=flat)   | ![forks](https://img.shields.io/github/forks/alexflint/go-arg.svg)                                      | Struct-based argument parsing in Go                                                                                                    |
| [mow.cli](https://github.com/jawher/mow.cli)       | ![stars](http://githubbadges.com/star.svg?user=jawher&repo=mow.cli&style=flat)     | ![forks](https://img.shields.io/github/forks/jawher/mow.cli.svg)                                        | A versatile library for building CLI applications in Go                                                                                |
| [pflag](https://github.com/spf13/pflag)            | ![stars](http://githubbadges.com/star.svg?user=ogier&repo=pflag&style=flat)        | ![forks](https://img.shields.io/github/forks/spf13/pflag.svg)                                           | Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags.                                                       |
| [commandeer](https://github.com/jaffee/commandeer) | ![stars](http://githubbadges.com/star.svg?user=jaffee&repo=commandeer&style=flat)  | ![forks](https://img.shields.io/github/forks/jaffee/commandeer.svg)                                     | Commandeer sets up command line flags based on struct fields and tags.                                                                 |

## Console UI

|                           Repo                            |                  &nbsp;&nbsp;&nbsp;&nbsp;Stars&nbsp;&nbsp;&nbsp;&nbsp;                   |           &nbsp;&nbsp;&nbsp;&nbsp;Forks&nbsp;&nbsp;&nbsp;&nbsp;            |                                            Description                                             |
| --------------------------------------------------------- | ---------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| [lazygit](https://github.com/jesseduffield/lazygit)       | ![stars](http://githubbadges.com/star.svg?user=jesseduffield&repo=lazygit&style=flat)    | ![forks](https://img.shields.io/github/forks/jesseduffield/lazygit.svg)    | Simple terminal UI for git commands.                                                               |
| [lazydocker](https://github.com/jesseduffield/lazydocker) | ![stars](http://githubbadges.com/star.svg?user=jesseduffield&repo=lazydocker&style=flat) | ![forks](https://img.shields.io/github/forks/jesseduffield/lazydocker.svg) | The lazier way to manage everything docker.                                                        |
| [vuls](https://github.com/future-architect/vuls)          | ![stars](http://githubbadges.com/star.svg?user=future-architect&repo=vuls&style=flat)    | ![forks](https://img.shields.io/github/forks/future-architect/vuls.svg)    | Vulnerability scanner for Linux/FreeBSD, agentless, written in golang.                             |
| [jid](https://github.com/simeji/jid)                      | ![stars](http://githubbadges.com/star.svg?user=simeji&repo=jid&style=flat)               | ![forks](https://img.shields.io/github/forks/simeji/jid.svg)               | json incremental digger.                                                                           |
| [httplab](https://github.com/gchaincl/httplab)            | ![stars](http://githubbadges.com/star.svg?user=gchaincl&repo=httplab&style=flat)         | ![forks](https://img.shields.io/github/forks/gchaincl/httplab.svg)         | let you inspect HTTP requests and forge responses.                                                 |
| [color](https://github.com/fatih/color)                   | ![stars](http://githubbadges.com/star.svg?user=fatih&repo=color&style=flat)              | ![forks](https://img.shields.io/github/forks/fatih/color.svg)              | Color package for Go (golang).                                                                     |
| [dry](https://github.com/moncho/dry)                      | ![stars](http://githubbadges.com/star.svg?user=moncho&repo=dry&style=flat)               | ![forks](https://img.shields.io/github/forks/moncho/dry.svg)               | A Docker manager for the terminal.                                                                 |
| [fac](https://github.com/mkchoi212/fac)                   | ![stars](http://githubbadges.com/star.svg?user=mkchoi212&repo=fac&style=flat)            | ![forks](https://img.shields.io/github/forks/mkchoi212/fac.svg)            | Easy-to-use CUI for fixing git conflicts.                                                          |
| [if](https://github.com/gokcehan/lf)                      | ![stars](http://githubbadges.com/star.svg?user=gokcehan&repo=lf&style=flat)              | ![forks](https://img.shields.io/github/forks/gokcehan/lf.svg)              | Terminal file manager.                                                                             |
| [asciigraph](https://github.com/guptarohit/asciigraph)    | ![stars](http://githubbadges.com/star.svg?user=guptarohit&repo=asciigraph&style=flat)    | ![forks](https://img.shields.io/github/forks/guptarohit/asciigraph.svg)    | Go package to make lightweight ASCII line graphs ╭┈╯.                                              |
| [cointop](https://github.com/miguelmota/cointop)          | ![stars](http://githubbadges.com/star.svg?user=miguelmota&repo=cointop&style=flat)       | ![forks](https://img.shields.io/github/forks/miguelmota/cointop.svg)       | A interactive terminal for tracking cryptocurrency coin stats in real-time.                        |
| [rat](https://github.com/ericfreese/rat)                  | ![stars](http://githubbadges.com/star.svg?user=ericfreese&repo=rat&style=flat)           | ![forks](https://img.shields.io/github/forks/ericfreese/rat.svg)           | Compose shell commands to build interactive terminal applications.                                 |
| [mop](https://github.com/mop-tracker/mop)                 | ![stars](http://githubbadges.com/star.svg?user=mop-tracker&repo=mop&style=flat)          | ![forks](https://img.shields.io/github/forks/mop-tracker/mop.svg)          | Stock market tracker for hackers.                                                                  |
| [mpb](https://github.com/vbauerster/mpb)                  | ![stars](http://githubbadges.com/star.svg?user=vbauerster&repo=mpb&style=flat)           | ![forks](https://img.shields.io/github/forks/vbauerster/mpb.svg)           | multi progress bar for Go cli applications.                                                        |
| [aurora](https://github.com/logrusorgru/aurora)           | ![stars](http://githubbadges.com/star.svg?user=logrusorgru&repo=aurora&style=flat)       | ![forks](https://img.shields.io/github/forks/logrusorgru/aurora.svg)       | Golang ultimate ANSI-colors that supports Printf/Sprintf methods.                                  |
| [pxl](https://github.com/ichinaski/pxl)                   | ![stars](http://githubbadges.com/star.svg?user=ichinaski&repo=pxl&style=flat)            | ![forks](https://img.shields.io/github/forks/ichinaski/pxl.svg)            | Display images in the terminal.                                                                    |
| [progressbar](https://github.com/schollz/progressbar)     | ![stars](http://githubbadges.com/star.svg?user=schollz&repo=progressbar&style=flat)      | ![forks](https://img.shields.io/github/forks/schollz/progressbar.svg)      | A really basic thread-safe progress bar for Golang applications.                                   |
| [diagram](https://github.com/esimov/diagram)              | ![stars](http://githubbadges.com/star.svg?user=esimov&repo=diagram&style=flat)           | ![forks](https://img.shields.io/github/forks/esimov/diagram.svg)           | Diagram is a CLI tool to generate hand drawn diagrams from ASCII arts.                             |
| [clui](https://github.com/VladimirMarkelov/clui)          | ![stars](http://githubbadges.com/star.svg?user=VladimirMarkelov&repo=clui&style=flat)    | ![forks](https://img.shields.io/github/forks/VladimirMarkelov/clui.svg)    | Terminal cli app that checks the availability of domains for different configurations of keywords. |
| [gomainr](https://github.com/MichaelThessel/gomainr)      | ![stars](http://githubbadges.com/star.svg?user=MichaelThessel&repo=gomainr&style=flat)   | ![forks](https://img.shields.io/github/forks/MichaelThessel/gomainr.svg)   | Terminal cli app that checks the availability of domains for different configurations of keywords. |

### Console UI Engine/Library

|                        Repo                        |                &nbsp;&nbsp;&nbsp;&nbsp;Stars&nbsp;&nbsp;&nbsp;&nbsp;                |         &nbsp;&nbsp;&nbsp;&nbsp;Forks&nbsp;&nbsp;&nbsp;&nbsp;         |                                                                         Description                                                                          |
| -------------------------------------------------- | ----------------------------------------------------------------------------------- | --------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [termui](https://github.com/gizak/termui)          | ![stars](http://githubbadges.com/star.svg?user=gizak&repo=termui&style=flat)        | ![forks](https://img.shields.io/github/forks/gizak/termui.svg)        | Golang terminal dashboard.                                                                                                                                   |
| [gocui](https://github.com/jroimartin/gocui)       | ![stars](http://githubbadges.com/star.svg?user=jroimartin&repo=gocui&style=flat)    | ![forks](https://img.shields.io/github/forks/jroimartin/gocui.svg)    | Minimalist Go package aimed at creating Console User Interfaces.                                                                                             |
| [termbox-go](https://github.com/nsf/termbox-go)    | ![stars](http://githubbadges.com/star.svg?user=nsf&repo=termbox-go&style=flat)      | ![forks](https://img.shields.io/github/forks/nsf/termbox-go.svg)      | provides a minimalistic API which allows the programmer to write text-based user interfaces.                                                                 |
| [tview](https://github.com/rivo/tview)             | ![stars](http://githubbadges.com/star.svg?user=rivo&repo=tview&style=flat)          | ![forks](https://img.shields.io/github/forks/rivo/tview.svg)          | Rich interactive widgets for terminal-based UIs written in Go.                                                                                               |
| [go-prompt](https://github.com/c-bata/go-prompt)   | ![stars](http://githubbadges.com/star.svg?user=c-bata&repo=go-prompt&style=flat)    | ![forks](https://img.shields.io/github/forks/c-bata/go-prompt.svg)    | A library for building powerful interactive prompts inspired by python-prompt-toolkit, making it easier to build cross-platform command line tools using Go. |
| [tui-go](https://github.com/marcusolsson/tui-go)   | ![stars](http://githubbadges.com/star.svg?user=marcusolsson&repo=tui-go&style=flat) | ![forks](https://img.shields.io/github/forks/marcusolsson/tui-go.svg) | A UI library for terminal applications.                                                                                                                      |
| [uiprogress](https://github.com/gosuri/uiprogress) | ![stars](http://githubbadges.com/star.svg?user=gosuri&repo=uiprogress&style=flat)   | ![forks](https://img.shields.io/github/forks/gosuri/uiprogress.svg)   | A go library to render progress bars in terminal applications                                                                                                |
| [gcli](https://github.com/tcnksm/gcli)             | ![stars](http://githubbadges.com/star.svg?user=tcnksm&repo=gcli&style=flat)         | ![forks](https://img.shields.io/github/forks/tcnksm/gcli.svg)         | Generates a skeleton you need to start building CLI tool by Golang.                                                                                          |
| [uilive](https://github.com/gosuri/uilive)         | ![stars](http://githubbadges.com/star.svg?user=gosuri&repo=uilive&style=flat)       | ![forks](https://img.shields.io/github/forks/gosuri/uilive.svg)       | uilive is a go library for updating terminal output in realtime.                                                                                             |
| [termdash](https://github.com/mum4k/termdash)      | ![stars](http://githubbadges.com/star.svg?user=mum4k&repo=termdash&style=flat)      | ![forks](https://img.shields.io/github/forks/mum4k/termdash.svg)      | a cross-platform customizable terminal based dashboard.                                                                                                      |
| [uitable](https://github.com/gosuri/uitable)       | ![stars](http://githubbadges.com/star.svg?user=gosuri&repo=uitable&style=flat)      | ![forks](https://img.shields.io/github/forks/gosuri/uitable.svg)      | A go library to improve readability in terminal apps using tabular data.                                                                                     |

## Web Frameworks

|                           Repo                            |                  &nbsp;&nbsp;&nbsp;&nbsp;Stars&nbsp;&nbsp;&nbsp;&nbsp;                   |                             &nbsp;&nbsp;&nbsp;&nbsp;Forks&nbsp;&nbsp;&nbsp;&nbsp;                              |                                                      Description                                                       |
| --------------------------------------------------------- | ---------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| [gin](https://github.com/gin-gonic/gin)                   | ![stars](http://githubbadges.com/star.svg?user=gin-gonic&repo=gin&style=flat)            | ![stars](http://githubbadges.com/fork.svg?user=gin-gonic&repo=gin&style=flat&color=fff&background=1282C2)      | A HTTP web framework written in Go. It features a Martini-like API with much better performance (40x faster).          |
| [beego](https://github.com/astaxie/beego)                 | ![stars](http://githubbadges.com/star.svg?user=astaxie&repo=beego&style=flat)            | ![stars](http://githubbadges.com/fork.svg?user=astaxie&repo=beego&style=flat&color=fff&background=1282C2)      | beego is an open-source, high-performance web framework for the Go programming language.                               |
| [iris](https://github.com/kataras/iris)                   | ![stars](http://githubbadges.com/star.svg?user=kataras&repo=iris&style=flat)             | ![stars](http://githubbadges.com/fork.svg?user=kataras&repo=iris&style=flat&color=fff&background=1282C2)       | The fastest web framework for Go in (THIS) Earth. HTTP/2 Ready to GO. MVC when you need it.                            |
| [echo](https://github.com/labstack/echo)                  | ![stars](http://githubbadges.com/star.svg?user=labstack&repo=echo&style=flat)            | ![stars](http://githubbadges.com/fork.svg?user=labstack&repo=echo&style=flat&color=fff&background=1282C2)      | High performance, minimalist Go web framework                                                                          |
| [revel](https://github.com/revel/revel)                   | ![stars](http://githubbadges.com/star.svg?user=revel&repo=revel&style=flat)              | ![stars](http://githubbadges.com/fork.svg?user=revel&repo=revel&style=flat&color=fff&background=1282C2)        | A high productivity, full-stack web framework for the Go language.                                                     |
| [martini](https://github.com/go-martini/martini)          | ![stars](http://githubbadges.com/star.svg?user=go-martini&repo=martini&style=flat)       | ![stars](http://githubbadges.com/fork.svg?user=go-martini&repo=martini&style=flat&color=fff&background=1282C2) | Classy web framework for Go                                                                                            |
| [httprouter](https://github.com/julienschmidt/httprouter) | ![stars](http://githubbadges.com/star.svg?user=julienschmidt&repo=httprouter&style=flat) | ![stars](https://img.shields.io/github/forks/julienschmidt/httprouter.svg)                                     | A high performance HTTP request router that scales well                                                                |
| [mux](https://github.com/gorilla/mux)                     | ![stars](http://githubbadges.com/star.svg?user=gorilla&repo=mux&style=flat)              | ![stars](https://img.shields.io/github/forks/gorilla/mux.svg)                                                  | A powerful URL router and dispatcher for golang.                                                                       |
| [fasthttp](https://github.com/valyala/fasthttp)           | ![stars](http://githubbadges.com/star.svg?user=valyala&repo=fasthttp&style=flat)         | ![stars](https://img.shields.io/github/forks/valyala/fasthttp.svg)                                             | Fast HTTP package for Go. Tuned for high performance. Zero memory allocations in hot paths. (10x faster than net/http) |
| [chi](https://github.com/go-chi/chi)                      | ![stars](http://githubbadges.com/star.svg?user=go-chi&repo=chi&style=flat)               | ![stars](https://img.shields.io/github/forks/go-chi/chi.svg)                                                   | lightweight, idiomatic and composable router for building Go HTTP services                                             |
| [buffalo](https://github.com/gobuffalo/buffalo)           | ![stars](http://githubbadges.com/star.svg?user=gobuffalo&repo=buffalo&style=flat)        | ![stars](https://img.shields.io/github/forks/gobuffalo/buffalo.svg)                                            | Rapid Web Development w/ Go                                                                                            |
| [go-swagger](https://github.com/go-swagger/go-swagger)    | ![stars](http://githubbadges.com/star.svg?user=go-swagger&repo=go-swagger&style=flat)    | ![stars](https://img.shields.io/github/forks/go-swagger/go-swagger.svg)                                        | Swagger 2.0 implementation for go                                                                                      |
| [goa](https://github.com/goadesign/goa)                   | ![stars](http://githubbadges.com/star.svg?user=goadesign&repo=goa&style=flat)            | ![stars](https://img.shields.io/github/forks/goadesign/goa.svg)                                                | Design-based APIs and microservices in Go                                                                              |
| [go-restful](https://github.com/emicklei/go-restful)      | ![stars](http://githubbadges.com/star.svg?user=emicklei&repo=go-restful&style=flat)      | ![stars](https://img.shields.io/github/forks/emicklei/go-restful.svg)                                          | package for building REST-style Web Services using Google Go                                                           |
| [go-json-rest](https://github.com/ant0ine/go-json-rest)   | ![stars](http://githubbadges.com/star.svg?user=ant0ine&repo=go-json-rest&style=flat)     | ![stars](https://img.shields.io/github/forks/ant0ine/go-json-rest.svg)                                         | A quick and easy way to setup a RESTful JSON API                                                                       |
| [gizmo](https://github.com/NYTimes/gizmo)                 | ![stars](http://githubbadges.com/star.svg?user=NYTimes&repo=gizmo&style=flat)            | ![stars](https://img.shields.io/github/forks/NYTimes/gizmo.svg)                                                | A Microservice Toolkit from The New York Times                                                                         |
| [macaron](https://github.com/go-macaron/macaron)          | ![stars](http://githubbadges.com/star.svg?user=go-macaron&repo=macaron&style=flat)       | ![stars](https://img.shields.io/github/forks/go-macaron/macaron.svg)                                           | Package macaron is a high productive and modular web framework in Go.                                                  |
| [armor](https://github.com/labstack/armor)                | ![stars](http://githubbadges.com/star.svg?user=labstack&repo=armor&style=flat)           | ![stars](https://img.shields.io/github/forks/labstack/armor.svg)                                               | Uncomplicated, modern HTTP server                                                                                      |
| [web](https://github.com/gocraft/web)                     | ![stars](http://githubbadges.com/star.svg?user=gocraft&repo=web&style=flat)              | ![stars](https://img.shields.io/github/forks/gocraft/web.svg)                                                  | Go Router + Middleware. Your Contexts.                                                                                 |
| [tango](https://github.com/lunny/tango)                   | ![stars](http://githubbadges.com/star.svg?user=lunny&repo=tango&style=flat)              | ![stars](https://img.shields.io/github/forks/lunny/tango.svg)                                                  | Micro & pluggable web framework for Go                                                                                 |
| [goji](https://github.com/goji/goji)                      | ![stars](http://githubbadges.com/star.svg?user=goji&repo=goji&style=flat)                | ![stars](https://img.shields.io/github/forks/goji/goji.svg)                                                    | Goji is a minimalistic and flexible HTTP request multiplexer for Go (golang)                                           |
| [neo](https://github.com/ivpusic/neo)                     | ![stars](http://githubbadges.com/star.svg?user=ivpusic&repo=neo&style=flat)              | ![stars](https://img.shields.io/github/forks/ivpusic/neo.svg)                                                  | Go Web Framework                                                                                                       |
| [webgo](https://github.com/bnkamalesh/webgo)              | ![stars](http://githubbadges.com/star.svg?user=bnkamalesh&repo=webgo&style=flat)         | ![stars](https://img.shields.io/github/forks/bnkamalesh/webgo.svg)                                             | A very lightweight & simple web framework for Go                                                                       |
| [gorest](https://github.com/tideland/gorest)              | ![stars](http://githubbadges.com/star.svg?user=tideland&repo=gorest&style=flat)          | ![stars](https://img.shields.io/github/forks/tideland/gorest.svg)                                              | Tideland Go REST Server Library                                                                                        |

## Game

|                          Repo                          |                 &nbsp;&nbsp;&nbsp;&nbsp;Stars&nbsp;&nbsp;&nbsp;&nbsp;                 |          &nbsp;&nbsp;&nbsp;&nbsp;Forks&nbsp;&nbsp;&nbsp;&nbsp;          |                    Description                     |
| ------------------------------------------------------ | ------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- | -------------------------------------------------- |
| [go-astar](https://github.com/beefsack/go-astar)       | ![stars](http://githubbadges.com/star.svg?user=beefsack&repo=go-astar&style=flat)     | ![forks](https://img.shields.io/github/forks/beefsack/go-astar.svg)     | Go implementation of the A* search algorithm.      |
| [gotetris](https://github.com/jjinux/gotetris)         | ![stars](http://githubbadges.com/star.svg?user=jjinux&repo=gotetris&style=flat)       | ![forks](https://img.shields.io/github/forks/jjinux/gotetris.svg)       | A console-based version of Tetris written in Go.   |
| [snake-game](https://github.com/DyegoCosta/snake-game) | ![stars](http://githubbadges.com/star.svg?user=DyegoCosta&repo=snake-game&style=flat) | ![forks](https://img.shields.io/github/forks/DyegoCosta/snake-game.svg) | Terminal-based Snake game.                         |
| [sokoban-go](https://github.com/rn2dy/sokoban-go)      | ![stars](http://githubbadges.com/star.svg?user=rn2dy&repo=sokoban-go&style=flat)      | ![forks](https://img.shields.io/github/forks/rn2dy/sokoban-go.svg)      | Sokoban game in terminal written with go.          |
| [go-tetris](https://github.com/MichaelS11/go-tetris)   | ![stars](http://githubbadges.com/star.svg?user=MichaelS11&repo=go-tetris&style=flat)  | ![forks](https://img.shields.io/github/forks/MichaelS11/go-tetris.svg)  | Golang Tetris for console window with optional AI. |

### Game engine

|                          Repo                           |                &nbsp;&nbsp;&nbsp;&nbsp;Stars&nbsp;&nbsp;&nbsp;&nbsp;                 |         &nbsp;&nbsp;&nbsp;&nbsp;Forks&nbsp;&nbsp;&nbsp;&nbsp;          |                                Description                                 |
| ------------------------------------------------------- | ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| [leaf](https://github.com/name5566/leaf)                | ![stars](http://githubbadges.com/star.svg?user=name5566&repo=leaf&style=flat)        | ![forks](https://img.shields.io/github/forks/name5566/leaf.svg)        | A game server framework in Go.                                             |
| [pixel](https://github.com/faiface/pixel)               | ![stars](http://githubbadges.com/star.svg?user=faiface&repo=pixel&style=flat)        | ![forks](https://img.shields.io/github/forks/faiface/pixel.svg)        | A hand-crafted 2D game library in Go.                                      |
| [ebiten](https://github.com/hajimehoshi/ebiten)         | ![stars](http://githubbadges.com/star.svg?user=hajimehoshi&repo=ebiten&style=flat)   | ![forks](https://img.shields.io/github/forks/hajimehoshi/ebiten.svg)   | A dead simple 2D game library in Go.                                       |
| [goworld](https://github.com/xiaonanln/goworld)         | ![stars](http://githubbadges.com/star.svg?user=xiaonanln&repo=goworld&style=flat)    | ![forks](https://img.shields.io/github/forks/xiaonanln/goworld.svg)    | Scalable Distributed Game Server Engine with Hot Swapping in Golang.       |
| [go-sdl2](https://github.com/veandco/go-sdl2)           | ![stars](http://githubbadges.com/star.svg?user=veandco&repo=go-sdl2&style=flat)      | ![forks](https://img.shields.io/github/forks/veandco/go-sdl2.svg)      | Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/).   |
| [engo](https://github.com/EngoEngine/engo)              | ![stars](http://githubbadges.com/star.svg?user=EngoEngine&repo=engo&style=flat)      | ![forks](https://img.shields.io/github/forks/EngoEngine/engo.svg)      | An open-source 2D game engine written in Go.                               |
| [gonet](https://github.com/xtaci/gonet)                 | ![stars](http://githubbadges.com/star.svg?user=xtaci&repo=gonet&style=flat)          | ![forks](https://img.shields.io/github/forks/xtaci/gonet.svg)          | A Game Server Skeleton in golang.                                          |
| [termloop](https://github.com/JoelOtter/termloop)       | ![stars](http://githubbadges.com/star.svg?user=JoelOtter&repo=termloop&style=flat)   | ![forks](https://img.shields.io/github/forks/JoelOtter/termloop.svg)   | Terminal-based game engine for Go, built on top of Termbox                 |
| [nano](https://github.com/lonng/nano)                   | ![stars](http://githubbadges.com/star.svg?user=lonng&repo=nano&style=flat)           | ![forks](https://img.shields.io/github/forks/lonng/nano.svg)           | Lightweight, facility, high performance golang based game server framework |
| [engine](https://github.com/g3n/engine)                 | ![stars](http://githubbadges.com/star.svg?user=g3n&repo=engine&style=flat)           | ![forks](https://img.shields.io/github/forks/g3n/engine.svg)           | Go 3D Game Engine.                                                         |
| [oak](https://github.com/oakmound/oak)                  | ![stars](http://githubbadges.com/star.svg?user=oakmound&repo=oak&style=flat)         | ![forks](https://img.shields.io/github/forks/oakmound/oak.svg)         | A pure Go game engine.                                                     |
| [engine](https://github.com/azul3d/engine)              | ![stars](http://githubbadges.com/star.svg?user=azul3d&repo=engine&style=flat)        | ![forks](https://img.shields.io/github/forks/azul3d/engine.svg)        | A 3D game engine written in Go.                                            |
| [raylib-go](https://github.com/gen2brain/raylib-go)     | ![stars](http://githubbadges.com/star.svg?user=gen2brain&repo=raylib-go&style=flat)  | ![forks](https://img.shields.io/github/forks/gen2brain/raylib-go.svg)  | A pure Go game engine.                                                     |
| [GarageEngine](https://github.com/vova616/GarageEngine) | ![stars](http://githubbadges.com/star.svg?user=vova616&repo=GarageEngine&style=flat) | ![forks](https://img.shields.io/github/forks/vova616/GarageEngine.svg) | Game engine written in Go.                                                 |