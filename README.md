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
2026-02-02T21:00:13.074923+00:00
```

### Most recent CVE Modification Timestamp synchronized with NVD

```plain
2026-02-02T20:59:44.750000+00:00
```

### Last Data Feed Release

Download and Changelog: [Click](https://github.com/fkie-cad/nvd-json-data-feeds/releases/latest)

```plain
2026-02-02T01:00:02.115995+00:00
```

### Total Number of included CVEs

```plain
330555
```

### CVEs added in the last Commit

Recently added CVEs: `0`



### CVEs modified in the last Commit

Recently modified CVEs: `41`

- [CVE-2026-1521](CVE-2026/CVE-2026-15xx/CVE-2026-1521.json) (`2026-02-02T19:44:26.477`)
- [CVE-2026-1522](CVE-2026/CVE-2026-15xx/CVE-2026-1522.json) (`2026-02-02T19:23:51.507`)
- [CVE-2026-1534](CVE-2026/CVE-2026-15xx/CVE-2026-1534.json) (`2026-02-02T20:59:44.750`)
- [CVE-2026-1545](CVE-2026/CVE-2026-15xx/CVE-2026-1545.json) (`2026-02-02T19:41:32.603`)
- [CVE-2026-1551](CVE-2026/CVE-2026-15xx/CVE-2026-1551.json) (`2026-02-02T19:26:59.780`)
- [CVE-2026-1589](CVE-2026/CVE-2026-15xx/CVE-2026-1589.json) (`2026-02-02T19:25:56.550`)
- [CVE-2026-1590](CVE-2026/CVE-2026-15xx/CVE-2026-1590.json) (`2026-02-02T19:25:13.073`)
- [CVE-2026-1593](CVE-2026/CVE-2026-15xx/CVE-2026-1593.json) (`2026-02-02T20:54:26.120`)
- [CVE-2026-1594](CVE-2026/CVE-2026-15xx/CVE-2026-1594.json) (`2026-02-02T20:53:42.123`)
- [CVE-2026-1595](CVE-2026/CVE-2026-15xx/CVE-2026-1595.json) (`2026-02-02T20:52:57.747`)
- [CVE-2026-20411](CVE-2026/CVE-2026-204xx/CVE-2026-20411.json) (`2026-02-02T19:16:12.193`)
- [CVE-2026-21696](CVE-2026/CVE-2026-216xx/CVE-2026-21696.json) (`2026-02-02T20:40:21.660`)
- [CVE-2026-21859](CVE-2026/CVE-2026-218xx/CVE-2026-21859.json) (`2026-02-02T19:16:52.987`)
- [CVE-2026-21869](CVE-2026/CVE-2026-218xx/CVE-2026-21869.json) (`2026-02-02T19:12:36.020`)
- [CVE-2026-21896](CVE-2026/CVE-2026-218xx/CVE-2026-21896.json) (`2026-02-02T19:02:51.850`)
- [CVE-2026-22218](CVE-2026/CVE-2026-222xx/CVE-2026-22218.json) (`2026-02-02T20:56:44.393`)
- [CVE-2026-22219](CVE-2026/CVE-2026-222xx/CVE-2026-22219.json) (`2026-02-02T20:56:09.457`)
- [CVE-2026-23625](CVE-2026/CVE-2026-236xx/CVE-2026-23625.json) (`2026-02-02T20:49:09.927`)
- [CVE-2026-23646](CVE-2026/CVE-2026-236xx/CVE-2026-23646.json) (`2026-02-02T20:46:13.157`)
- [CVE-2026-23721](CVE-2026/CVE-2026-237xx/CVE-2026-23721.json) (`2026-02-02T20:44:39.410`)
- [CVE-2026-23961](CVE-2026/CVE-2026-239xx/CVE-2026-23961.json) (`2026-02-02T20:29:07.753`)
- [CVE-2026-23962](CVE-2026/CVE-2026-239xx/CVE-2026-23962.json) (`2026-02-02T20:27:51.360`)
- [CVE-2026-23963](CVE-2026/CVE-2026-239xx/CVE-2026-23963.json) (`2026-02-02T20:27:15.387`)
- [CVE-2026-23964](CVE-2026/CVE-2026-239xx/CVE-2026-23964.json) (`2026-02-02T20:26:10.053`)
- [CVE-2026-24435](CVE-2026/CVE-2026-244xx/CVE-2026-24435.json) (`2026-02-02T19:56:16.290`)


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

## Bot Source Code

The bot's source code is available at [fkie-cad/nvd\_json\_bot](https://github.com/fkie-cad/nvd_json_bot).