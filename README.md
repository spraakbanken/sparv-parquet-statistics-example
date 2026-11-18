# sparv-parquet-statistics-example

## Installation

Setup the environment with `uv sync`.

## Usage

- Activate the virtual environment: `source .venv/bin/activate`
- Copy all your parquet files to `examples/parquet_statistics/source`
  - (you can delete the existing file.)
  - Nested directories are okay.
- `cd examples/parquet_statistics`
- Setup sparv: `sparv setup`, and press Enter
- Run sparv: `sparv run`
  - If you need more logging add `--log-to-file debug`
  - You can also specify how many threads with: `-j <NUM>`
- If the run is successful, the statistics can be found in `export/sbx_corpus_statistics.stat_highlights`

If you run into any problems, please report them to this repository or https://github.com/spraakbanken/sparv-sbx-corpus-statistics/issues
