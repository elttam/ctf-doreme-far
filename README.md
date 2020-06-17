# Overview

**Title:** Doreme Far
**Category:** Web
**Flag:** libctf{151ee273-0b84-4b1c-88e4-614f03586f4d}
**Difficulty:** Trivial

# Usage

The following will pull the latest 'elttam/ctf-doreme-far' image from DockerHub, run a new container named 'libctfso-doreme-far', and publish the vulnerable service on port 80:

```sh
docker run --rm \
  --publish 80:80 \
  --name libctfso-doreme-far \
  elttam/ctf-doreme-far:latest
```

# Build (Optional)

If you prefer to build the 'elttam/ctf-doreme-far' image yourself you can do so first with:

```sh
docker build ${PWD} \
  --tag elttam/ctf-doreme-far:latest
```

