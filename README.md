
Minimal cljs deploy
----

> Minimal steps to publish a ClojureScript libaray, based on [deps-library](https://github.com/appliedsciencestudio/deps-library) .

### Usages

Prepare an account for https://clojars.org/ before you start. And your code in `src/`. Then:

* Check `deps.edn` for paths and dependencies.
* Update `release.edn` for package informations.
* Run command to deploy:

```bash
CLOJARS_USERNAME=TODO CLOJARS_PASSWORD=TOOD clj -A:release
```

Send feedbacks to [GitHub](https://github.com/appliedsciencestudio/deps-library) if you got trouble.

### License

MIT
