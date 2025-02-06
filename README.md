### Hi there 👋

> Note: my Github username changed from metadave to bookshelfdave in late 2021

I'm currently a Principal Lead Software Engineer at [Akamai](https://www.akamai.com/) ([Linode](https://www.linode.com/)), working on Linode orchestration software (all closed source). I helped ship [Firefox](https://www.mozilla.org/en-US/firefox/new/) ([1](https://www.mozilla.org/credits/)), the [Terraform Plugin Framework](https://www.hashicorp.com/blog/terraform-plugin-framework-is-now-generally-available), [Chef Server](https://github.com/chef/chef-server/), [Chef Analytics](https://www.chef.io/blog/meet-the-chef-analytics-platform), [Habitat](https://community.chef.io/tools/chef-habitat), VLC compiler and Varnish projects at [Fastly](https://www.fastly.com/), and [Riak Multi Data Center Replication](https://docs.riak.com/riak/kv/latest/using/cluster-operations/v3-multi-datacenter/index.html). 

- I'm interested in:
	- distributed systems
	- programming language theory + functional programming
	- parsing + compilers
	- infrastructure automation
	- polyglot software development
	  - I use C, Python, Terraform, C#, Go, Ruby, Swift, C++ etc.
	  - I ♥️ Rust, Haskell, Erlang, F#, OCaml, Racket, etc.
	- math + 3d geometry
- Remote worker since 2012
- 👯 I’m looking to collaborate on
  - compilers + language runtimes
  - cloud infrastructure tooling
  - audio / synth stuff
    - I [play](https://vimeo.com/259783641) [guitar](https://vimeo.com/686513948), although I am not a performer.
   
      
<a name="portfolio"></a>

# Fun projects that I've worked on over the years 

- [Mars 2020 Helicopter Contributor](https://github.com/readme/featured/nasa-ingenuity-helicopter)
  - A badge appears under my Github profile picture
  - [my contributions to Elasicsearch](https://github.com/elastic/elasticsearch/pull/12534)

### Books that I've reviewed (and am credited for)

- [Haskell (Almost) Standard Libraries](https://leanpub.com/haskell-stdlibs/), by Alejandro Serrano Mena (March 2022)
- [7 Databases in 7 Weeks, second edition](https://7dbs.io/) by By Luc Perkins, Eric Redmond, and Jim Wilson
- [The Design And Implementation Of The Freebsd Operating System 1st Edition](https://www.amazon.com/Design-Implementation-FreeBSD-Operating-System/dp/0201702452/ref=sr_1_2?keywords=the+design+and+implementation+of+the+freebsd+operating+system&qid=1647620400&s=books&sprefix=the+design+and+implemenat%2Cstripbooks%2C68&sr=1-2), by Marshall Kirk McKusick and George V. Neville-Neil 


### Habitat

- [102 PR's](https://github.com/habitat-sh/habitat/pulls?q=is%3Apr+author%3Abookshelfdave+is%3Aclosed) against [Habitat](https://habitat.sh), mostly Rust
  - a few highlights:
    - [Add encrypted file upload to gossip ring](https://github.com/habitat-sh/habitat/pull/452)
    - [Add artifact sign/verify with libsodium](https://github.com/habitat-sh/habitat/pull/357)
    - [Habitat Director](https://github.com/habitat-sh/habitat/pull/541)
    - [Encryption / decryption support](https://github.com/habitat-sh/habitat/pull/171)
- and [a patent](https://www.uspto.report/patent/app/20170351868) as well! 

### Cloud/infra "stuff" (K8s, Chef, etc)

- [223 commits](https://github.com/mozmeao/infra/pulls?q=is%3Apr+is%3Aclosed+author%3Abookshelfdave) as an SRE on the Mozilla Marketing Engineering and Ops (MozMEAO) team (Terraform, Python, Ansible, K8s)
  - This team hosted [www.mozilla.org](https://www.mozilla.org), [developer.mozilla.org](https://developer.mozilla.org), [careers.mozilla.org](https://careers.mozilla.org) along with other Mozilla services and sites.
- Contributor to the Velero backup tool for Kubernetes (Go)
	- [Add an `ark bug` command](https://github.com/vmware-tanzu/velero/pull/774) (Go)
- [ksv: K8s Secrets Viewer](https://github.com/bookshelfdave/ksv) (Go)
  - and a [version of ksv written in Python](https://github.com/bookshelfdave/ksv.py)
- [Riemann OCaml Client](https://github.com/bookshelfdave/riemann-ocaml-client)
- Chef Server [RabbitMQ queue monitor](https://github.com/chef/chef-server/pull/570) (Erlang / Chef)
- [Implement profile signing and verification for Chef Inspec](https://github.com/inspec/inspec/pull/1228) (Ruby)


### Parsing/language stuff
- I added [support for scientific notation](https://github.com/gleam-lang/gleam/pull/1903) to the [Gleam programming language](https://gleam.run/) (Dec 2022).
- [Contributions to Disco](https://github.com/disco-lang/disco/pulls?q=is%3Apr+author%3A%40me+is%3Aclosed), a discrete math teaching language written in Haskell
  - the largest contribution being https://github.com/disco-lang/disco/pull/230
  - add [OEIS](https://oeis.org/) support to the Disco language: https://github.com/disco-lang/disco/pull/202
- [Chef Analytics Rules](https://docs-archive.chef.io/release/analytics/analytics_rules.html), discontinued (Java, Antlr, Apache Storm)
- [JKVC](https://github.com/bookshelfdave/JKVC) - Key Value Coding for Java data structures
- [ETP](https://github.com/bookshelfdave/etp): an Erlang Term Parser for Java.
- [EQL: an Elasticsearch Query Language (experimental)](https://github.com/bookshelfdave/eql) (Java/Antlr)
- [StringTemplate Object Wrappers](https://github.com/bookshelfdave/stow) (Java/Antlr)

### [Riak](https://en.wikipedia.org/wiki/Riak)

- [Riak C client](https://github.com/bookshelfdave/riak-c-client)
- [Riak R client](https://github.com/bookshelfdave/riak-r-client)
	- original author, although the client changed a bit
- [Riak OCaml client](https://github.com/bookshelfdave/riak-ocaml-client)
- [89 PR's](https://github.com/basho/riak_repl/pulls?q=is%3Apr+author%3Abookshelfdave+is%3Aclosed) against Riak multi datacenter replication (MDC)
  - Riak MDC replication ["proxy get"](https://github.com/basho/riak_repl/pull/75)
- [Contact](https://github.com/bookshelfdave/contact): a query language and interactive shell for Riak. (Java/Antlr/Javascript via Rhino)


### Misc

- [Wings3d Collada export plugin](https://github.com/bjorng/wings/blob/master/plugins_src/import_export/wpc_collada.erl) (Erlang)
- [Elasticsearch nodeattrs API enhancements](https://github.com/elastic/elasticsearch/pull/12534) (Java)
- [EduFS](https://github.com/bookshelfdave/edufs): learning FreeBSD filesystem and kernel internals (C / FreeBSD Kernel stuff)
- [Racket Neo4j client](https://github.com/bookshelfdave/neo4j.rkt) (Racket)
- [Flux3d](https://github.com/bookshelfdave/FluxModeler) C++/Qt/Python half-edge 3d model viewer, mostly collision detection of verts/edges/faces, triangulation, etc. 
  - I [embedded a Python interpreter into Flux3d](https://github.com/bookshelfdave/FluxModeler/blob/python_dead/src/FluxCore.cpp#L690) to add scripting support
- [obj2json](https://github.com/bookshelfdave/obj2json) 3d .obj -> .json converter written in Haskell

