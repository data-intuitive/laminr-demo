# {laminr} demo

This is a demo of the **{laminr}** package.

## Installation

Follow the installation instructions at https://laminr.lamin.ai. 

## Procedure

Open up `example_analysis.Rmd` in RStudio and run the code chunks.

![](images/run_chunk.png)

You can render the report by clicking the "Knit" button.

![](images/run_knit.png)

This will render a report that looks like this:

![](images/render.png)

Finally, you can deploy the report to Lamin by running the following code:

```bash
lamin save example_analysis.Rmd
```

This will deploy the report to Lamin. You can view the report at the URL provided.

![](images/results.png)

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE.md](LICENSE.md) file for details.
