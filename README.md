To reproduce:
```
./pants --owners-not-found-behavior=ignore --pants-ignore='["/dir/**"]' list dir/BUILD
```
