
## Dev

It's recommended to use the netlify dev command if you're wanting to modify any of the server functions, such as for raw link support:

```
npx netlify dev
```

## Using Docker
Simply run the following commands within this repository to spin up the instance locally using a Docker container

```
docker build -t reverse_shell_generator .

docker run -d -p 80:80 reverse_shell_generator
```

Browse to http://localhost:80

By Royaloakap
