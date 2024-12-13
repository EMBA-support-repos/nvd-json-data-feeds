# nvd-json-data-feeds

[![monitor-release](https://github.com/fkie-cad/nvd-json-data-feeds/actions/workflows/monitor_release.yml/badge.svg)](https://github.com/fkie-cad/nvd-json-data-feeds/actions/workflows/monitor_release.yml)
[![monitor-sync](https://github.com/fkie-cad/nvd-json-data-feeds/actions/workflows/monitor_sync.yml/badge.svg)](https://github.com/fkie-cad/nvd-json-data-feeds/actions/workflows/monitor_sync.yml)
[![validate-schema](https://github.com/fkie-cad/nvd-json-data-feeds/actions/workflows/validate_schema.yml/badge.svg)](https://github.com/fkie-cad/nvd-json-data-feeds/actions/workflows/validate_schema.yml)

Community reconstruction of the deprecated JSON NVD Data Feeds.
[Releases](https://github.com/fkie-cad/nvd-json-data-feeds/releases/latest) each day at 00:00 AM UTC.
Repository synchronizes with the NVD every 2 hours.

## Repository at a Glance

### Last Repository Update

```plain
2024-12-13T15:00:34.276447+00:00
```

### Most recent CVE Modification Timestamp synchronized with NVD

```plain
2024-12-13T14:53:21.583000+00:00
```

### Last Data Feed Release

Download and Changelog: [Click](https://github.com/fkie-cad/nvd-json-data-feeds/releases/latest)

```plain
2024-12-13T01:00:10.096882+00:00
```

### Total Number of included CVEs

```plain
273590
```

### CVEs added in the last Commit

Recently added CVEs: `6`

- [CVE-2024-11986](CVE-2024/CVE-2024-119xx/CVE-2024-11986.json) (`2024-12-13T14:15:21.207`)
- [CVE-2024-22461](CVE-2024/CVE-2024-224xx/CVE-2024-22461.json) (`2024-12-13T14:15:21.383`)
- [CVE-2024-38488](CVE-2024/CVE-2024-384xx/CVE-2024-38488.json) (`2024-12-13T14:15:21.993`)
- [CVE-2024-48007](CVE-2024/CVE-2024-480xx/CVE-2024-48007.json) (`2024-12-13T14:15:22.147`)
- [CVE-2024-48008](CVE-2024/CVE-2024-480xx/CVE-2024-48008.json) (`2024-12-13T14:15:22.273`)
- [CVE-2024-55889](CVE-2024/CVE-2024-558xx/CVE-2024-55889.json) (`2024-12-13T14:15:22.653`)


### CVEs modified in the last Commit

Recently modified CVEs: `20`

- [CVE-2017-9217](CVE-2017/CVE-2017-92xx/CVE-2017-9217.json) (`2024-12-13T14:15:18.280`)
- [CVE-2018-12122](CVE-2018/CVE-2018-121xx/CVE-2018-12122.json) (`2024-12-13T14:15:19.043`)
- [CVE-2018-12123](CVE-2018/CVE-2018-121xx/CVE-2018-12123.json) (`2024-12-13T14:15:19.250`)
- [CVE-2018-7738](CVE-2018/CVE-2018-77xx/CVE-2018-7738.json) (`2024-12-13T14:15:19.380`)
- [CVE-2023-29400](CVE-2023/CVE-2023-294xx/CVE-2023-29400.json) (`2024-12-13T14:15:19.623`)
- [CVE-2023-29402](CVE-2023/CVE-2023-294xx/CVE-2023-29402.json) (`2024-12-13T14:15:20.403`)
- [CVE-2023-43804](CVE-2023/CVE-2023-438xx/CVE-2023-43804.json) (`2024-12-13T14:15:20.570`)
- [CVE-2024-11691](CVE-2024/CVE-2024-116xx/CVE-2024-11691.json) (`2024-12-13T14:15:20.863`)
- [CVE-2024-11694](CVE-2024/CVE-2024-116xx/CVE-2024-11694.json) (`2024-12-13T14:15:21.053`)
- [CVE-2024-29131](CVE-2024/CVE-2024-291xx/CVE-2024-29131.json) (`2024-12-13T14:15:21.547`)
- [CVE-2024-29404](CVE-2024/CVE-2024-294xx/CVE-2024-29404.json) (`2024-12-13T14:15:21.740`)
- [CVE-2024-47241](CVE-2024/CVE-2024-472xx/CVE-2024-47241.json) (`2024-12-13T14:37:10.467`)
- [CVE-2024-53143](CVE-2024/CVE-2024-531xx/CVE-2024-53143.json) (`2024-12-13T14:15:22.443`)
- [CVE-2024-7254](CVE-2024/CVE-2024-72xx/CVE-2024-7254.json) (`2024-12-13T14:15:22.800`)
- [CVE-2024-8075](CVE-2024/CVE-2024-80xx/CVE-2024-8075.json) (`2024-12-13T14:46:14.797`)
- [CVE-2024-8076](CVE-2024/CVE-2024-80xx/CVE-2024-8076.json) (`2024-12-13T14:46:25.210`)
- [CVE-2024-8077](CVE-2024/CVE-2024-80xx/CVE-2024-8077.json) (`2024-12-13T14:50:34.863`)
- [CVE-2024-8078](CVE-2024/CVE-2024-80xx/CVE-2024-8078.json) (`2024-12-13T14:51:05.847`)
- [CVE-2024-8079](CVE-2024/CVE-2024-80xx/CVE-2024-8079.json) (`2024-12-13T14:53:21.583`)
- [CVE-2024-9681](CVE-2024/CVE-2024-96xx/CVE-2024-9681.json) (`2024-12-13T14:15:22.953`)


## Download and Usage

There are several ways you can work with the data in this repository:

### 1) Release Data Feed Packages

The most straightforward approach is to obtain the latest Data Feed release packages [here](https://github.com/fkie-cad/nvd-json-data-feeds/releases/latest).

Each day at 00:00 AM UTC we package and upload JSON files that aim to reconstruct the legacy NVD CVE Data Feeds.
Those are aggregated by the `year` part of the CVE identifier:

```
# CVE-<YEAR>.json
CVE-1999.json
CVE-2001.json
CVE-2002.json
CVE-2003.json
[...]
CVE-2023.json
CVE-2024.json
```

We also upload the well-known `Recent` and `Modified` feeds.
Furthermore, we provide the `All` feed, which contains a recent snapshot of all NVD records.
Once your local copy is synchronized and the last synchronization is no older than 8 days, you can rely on these to stay up to date:

```plain
CVE-Recent.json   # CVEs that were added in the previous eight days
CVE-Modified.json # CVEs that were modified or added in the previous eight days
```

Note that all feeds are distributed in `xz`-compressed format to save storage and bandwidth.
For decompression execute:

```sh
xz -d -k <feed>.json.xz
```

#### Automation using Release Data Feed Packages

You can fetch the latest releases for each package with the following static link layout:

```sh
https://github.com/fkie-cad/nvd-json-data-feeds/releases/latest/download/CVE-<YEAR>.json.xz
```

Example:

```sh
wget https://github.com/fkie-cad/nvd-json-data-feeds/releases/latest/download/CVE-2024.json.xz
xz -d -k CVE-2024.json.xz
```

### 2) Clone the Repository (with Git History)

As you can see by browsing this repository, there is a slight difference between the release packages format and the repository folder structure.
This is because we want to maintain explorability of the dataset.

Each CVE gets its own JSON file, e.g., `CVE-1999-0001.json`.
Here, each file is put into a folder layout that first sorts by CVE `year` identifier part and then by `number` part.
We mask (`xx`) the last two digits to create easily navigable folders that hold a maximum of 100 CVE JSON files:

```plain
.
├── CVE-1999
│   ├── CVE-1999-00xx
│   │   ├── CVE-1999-0001.json
│   │   ├── CVE-1999-0002.json
│   │   └── [...]
│   ├── CVE-1999-01xx
│   │   ├── CVE-1999-0101.json
│   │   └── [...]
│   └── [...]
├── CVE-2000
│   ├── CVE-2000-00xx
│   ├── CVE-2000-01xx
│   └── [...]
└── [...]
```

A byproduct of managing and continuously updating this dataset via Git is that we can track changes over time through the Git history.

If you are interested in having the NVD data as organized above, including the historical data of changes, just clone this repository (large!):

```sh
git clone https://github.com/fkie-cad/nvd-json-data-feeds.git
```

#### (Optional) Meta Files

Similar to the old official feeds, we provide meta files with each release. They can be fetched for each feed via:

```sh
https://github.com/fkie-cad/nvd-json-data-feeds/releases/latest/download/CVE-<YEAR>.meta
```

The structure is as follows:

```plain
lastModifiedDate:1970-01-01T00:00:00.000+00:00                          # ISO 8601 timestamp of last CVE modification
size:1000                                                               # size of uncompressed feed (bytes)
xzSize:100                                                              # size of lzma-compressed feed (bytes)
sha256:e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 # sha256 hexdigest of uncompressed feed
```

### 3) Clone the Repository (without Git History)

Don't need the history? Then create a shallow copy:

```sh
git clone --depth 1 -b main https://github.com/fkie-cad/nvd-json-data-feeds.git
```


## Update Timetable

* NVD Synchronization: `Bi-Hourly`, starting with `00:00:00Z`
* Release Packages: `Daily`, at `00:00:00Z`
* NVD Rebuilds: `Weekly`, at `Sun, 02:30:00Z`


## Motivation

On 2023-12-15, the NIST deprecated all [JSON-based NVD Data Feeds](https://nvd.nist.gov/vuln/data-feeds#divRetirementBanner-1).
The new [NVD CVE API 2.0](https://nvd.nist.gov/developers/vulnerabilities) is, without a doubt, a great way to obtain CVE information.
However, we from [Fraunhofer FKIE - Cyber Analysis and Defense](https://www.fkie.fraunhofer.de/en/departments/cad.html) believe that the API does not cover a variety of use cases.

The legacy NVD Data Feeds provided a convenient way to quickly obtain a complete, file-based offline database snapshot; just download the `CVE-<YEAR>.tar.gz`, decompress it, and use it as you please, e.g.:

- Put the JSON feed into a document-based database and quickly leverage upon that data in your software project, ...
- Parse and analyze it using your favorite programming language, ...
- Put it on a USB stick and transfer it to a system without internet access, or ...
- Query the file using `jq`!

Unfortunately, the new NVD API 2.0 adds complexity to this process.
We want to preserve ease of use by reconstructing these data sources.

## Non-Endorsement Clause

This project uses and redistributes data from the NVD API but is not endorsed or certified by the NVD.