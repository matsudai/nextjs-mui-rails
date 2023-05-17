### Template

```sh
docker network create nextjs-mui-rails_default
```

### Rails

```sh
gem install rails
rails new . --api --skip-test --database sqlite3 --skip-bundle

bundle
```

* Add `/vendor/bundle` >> `backend/.gitignore`

### Next.js

```sh
yarn create next-app xxxxx

    # yarn create v1.22.19
    # [1/4] Resolving packages...
    # [2/4] Fetching packages...
    # [3/4] Linking dependencies...
    # [4/4] Building fresh packages...
    #
    # success Installed "create-next-app@13.4.2" with binaries:
    #       - create-next-app
    # ? Would you like to use TypeScript with this project? … No / [Yes]
    # ? Would you like to use ESLint with this project? … No / [Yes]
    # ? Would you like to use Tailwind CSS with this project? … [No] / Yes
    # ? Would you like to use `src/` directory with this project? … [No] / Yes
    # ? Use App Router (recommended)? … No / [Yes]
    # ? Would you like to customize the default import alias? … [No] / Yes
```

* move `frontend/xxxxx/*` -> `frontend/`
