# Dash.js

## Step 1

``` python hl_lines="3 4"
""" Bubble sort """
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

## Step 2

<pre><code class="kotlin">DnaClient dnaClient = DnaClient.newBuilder()
    .context(<Context>)
    .playerInteractor(<PlayerInteractor>)
    .latency(<Integer>)
    .start(<Uri>);
</code></pre>

``` java tab="Kotlin"
DnaClient dnaClient = DnaClient.newBuilder()
    .context(<Context>)
    .playerInteractor(<PlayerInteractor>)
    .latency(<Integer>)
    .start(<Uri>);
```

``` java tab="Java"
DnaClient dnaClient = DnaClient.newBuilder()
    .context(<Context>)
    .playerInteractor(<PlayerInteractor>)
    .latency(<Integer>)
    .start(<Uri>);
```