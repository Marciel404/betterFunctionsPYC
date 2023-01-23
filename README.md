# NewFunctionsPYC

:A simple library for add new functions the Pycord

## Usage:
### install with pip

```shell
pip install -U git+https://github.com/Marciel404/NewFunctionsPYC
```

### Import on your code:

```python
import betterFunctions
```
### Run it
```python

Using embedBuilder:

    >>> from NewFunctionsPYC import embedBuilder
    >>> from hexacolors import stringColor # "pip install hexacolors" for use this
    >>>
    >>> e: embedBuilder = embedBuilder()
    >>>
    >>> e.set_title("Title")
    >>>
    >>> e.set_description("Description")
    >>>
    >>> e.set_color(stringColor("indigo"))
    >>>
    >>> channel.send(embed = e ) #List all colors availables
    
Using client:

    >>> import NewFunctionsPYC
    >>>
    >>> client = NewFunctionsPYC.client("tokenBot")
    >>>
    >>> client.load_cogs("commands")
    >>>
    >>> client.__run__()
        
```
