# Tired Dad Notes

Tired dad be new dad! Smol baby be cute, but no sleep much - so tired dad no sleep much. But is okay! Be tired make tired dad have lots of deep think about life with smol baby (deep think may also be onset of madness, tired dad not sure about that one). Tired dad write down to not forget! Also write down for you, to maybe have laugh (or maybe also despair, like tired dad sometime)!

Github workflow build notes on push, but if want build notes locally you run

```
docker run --rm -v "$(pwd):/data" -u $(id -u):$(id -g) pandoc/core --standalone --template template/index.html template/content.md -o index.html
```


