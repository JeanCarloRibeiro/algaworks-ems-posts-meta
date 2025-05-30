# **_Posts meta_**

**References:** _AlgaWorks EMS Training_


### Commands git submodules
download all submodules
```bash
git pull --recurse-submodules
```

add project as submodule (example: git submodule add <url> <path>)
```bash
git submodule add git@github.com:JeanCarloRibeiro/algaworks-ems-posts-meta.git microservices/post-service
```

clone all submodules (example: git clone --recurse-submodules <url>)

params: -j8: number of jobs to run in parallel
```bash 
git clone --recuse-submodules -j8 git@github.com:JeanCarloRibeiro/algaworks-ems-posts-meta.git posts-meta
```