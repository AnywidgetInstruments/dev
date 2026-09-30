# AnywidgetInstruments dev

Meta-repository aggregating all [AnywidgetInstruments](https://github.com/AnywidgetInstruments) repositories as git submodules.

## Clone

```sh
git clone --recurse-submodules git@github.com:AnywidgetInstruments/dev.git
```

or, in an existing clone:

```sh
git submodule update --init --recursive
```

## Update all submodules to their latest remote commit

```sh
git submodule update --remote --merge
```

## Submodules

| Path | Repository |
|------|------------|
| `afm-host-panel` | https://github.com/AnywidgetInstruments/afm-host-panel |
| `anywidget-instruments-automotive` | https://github.com/AnywidgetInstruments/anywidget-instruments-automotive |
| `anywidget-instruments-industrial` | https://github.com/AnywidgetInstruments/anywidget-instruments-industrial |
| `AnywidgetInstruments.jl` | https://github.com/AnywidgetInstruments/AnywidgetInstruments.jl |
| `Anywidget.jl` | https://github.com/AnywidgetInstruments/Anywidget.jl |
| `dotgithub` | https://github.com/AnywidgetInstruments/.github (organization profile and visual identity) |

> **Note:** [`anywidget-instruments`](https://github.com/AnywidgetInstruments/anywidget-instruments) is not included yet because the repository is currently empty. Add it once it has a first commit:
>
> ```sh
> git submodule add git@github.com:AnywidgetInstruments/anywidget-instruments.git anywidget-instruments
> ```
