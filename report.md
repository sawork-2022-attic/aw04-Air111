# aw04

## task1

`docker run -d --name web-pos-0.5 --cpus=0.5 -p 18080:8080 web-pos`

```
---- Global Information --------------------------------------------------------
> request count                                        100 (OK=100    KO=0     )
> min response time                                   2386 (OK=2386   KO=-     )
> max response time                                  11549 (OK=11549  KO=-     )
> mean response time                                  8389 (OK=8389   KO=-     )
> std deviation                                       2827 (OK=2827   KO=-     )
> response time 50th percentile                       9572 (OK=9572   KO=-     )
> response time 75th percentile                      10856 (OK=10856  KO=-     )
> response time 95th percentile                      11366 (OK=11366  KO=-     )
> response time 99th percentile                      11539 (OK=11539  KO=-     )
> mean requests/sec                                  8.333 (OK=8.333  KO=-     )
```