[![Release](https://jitpack.io/v/sssaikia/Slibe.svg?style=flat-square)]
(https://jitpack.io/#sssaikia/Slibe)


## RecyclerItemClickListener usage

```java
someRecyclerview.addOnItemTouchListener(
                new RecyclerItemClickListener(getActivity(), new RecyclerItemClickListener.OnItemClickListener() {
                    @Override
                    public void onItemClick(View view, int position) {
                        //DO stuff
                    }
                })
        );
```

## Google map route distance

```java

String distance= getDistance(final double lat1, final double lon1, final double lat2, final double lon2);

```
