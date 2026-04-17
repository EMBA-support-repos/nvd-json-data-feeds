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
2026-04-17T14:00:25.304922+00:00
```

### Most recent CVE Modification Timestamp synchronized with NVD

```plain
2026-04-17T13:36:35.750000+00:00
```

### Last Data Feed Release

Download and Changelog: [Click](https://github.com/fkie-cad/nvd-json-data-feeds/releases/latest)

```plain
2026-04-17T00:00:05.583804+00:00
```

### Total Number of included CVEs

```plain
345050
```

### CVEs added in the last Commit

Recently added CVEs: `11`

- [CVE-2025-46605](CVE-2025/CVE-2025-466xx/CVE-2025-46605.json) (`2026-04-17T12:16:31.843`)
- [CVE-2025-46606](CVE-2025/CVE-2025-466xx/CVE-2025-46606.json) (`2026-04-17T12:16:31.967`)
- [CVE-2025-46607](CVE-2025/CVE-2025-466xx/CVE-2025-46607.json) (`2026-04-17T12:16:32.087`)
- [CVE-2025-46641](CVE-2025/CVE-2025-466xx/CVE-2025-46641.json) (`2026-04-17T12:16:32.207`)
- [CVE-2026-23777](CVE-2026/CVE-2026-237xx/CVE-2026-23777.json) (`2026-04-17T12:16:32.343`)
- [CVE-2026-28263](CVE-2026/CVE-2026-282xx/CVE-2026-28263.json) (`2026-04-17T12:16:32.473`)
- [CVE-2026-6486](CVE-2026/CVE-2026-64xx/CVE-2026-6486.json) (`2026-04-17T13:16:14.117`)
- [CVE-2026-6487](CVE-2026/CVE-2026-64xx/CVE-2026-6487.json) (`2026-04-17T13:16:14.427`)
- [CVE-2026-6488](CVE-2026/CVE-2026-64xx/CVE-2026-6488.json) (`2026-04-17T13:16:14.603`)
- [CVE-2026-6489](CVE-2026/CVE-2026-64xx/CVE-2026-6489.json) (`2026-04-17T13:16:14.787`)
- [CVE-2026-6507](CVE-2026/CVE-2026-65xx/CVE-2026-6507.json) (`2026-04-17T13:16:14.967`)


### CVEs modified in the last Commit

Recently modified CVEs: `16`

- [CVE-2023-52356](CVE-2023/CVE-2023-523xx/CVE-2023-52356.json) (`2026-04-17T12:16:30.910`)
- [CVE-2025-14831](CVE-2025/CVE-2025-148xx/CVE-2025-14831.json) (`2026-04-17T12:16:31.377`)
- [CVE-2025-27363](CVE-2025/CVE-2025-273xx/CVE-2025-27363.json) (`2026-04-17T13:36:35.750`)
- [CVE-2025-57735](CVE-2025/CVE-2025-577xx/CVE-2025-57735.json) (`2026-04-17T13:03:16.150`)
- [CVE-2025-62188](CVE-2025/CVE-2025-621xx/CVE-2025-62188.json) (`2026-04-17T12:57:33.973`)
- [CVE-2025-70810](CVE-2025/CVE-2025-708xx/CVE-2025-70810.json) (`2026-04-17T13:06:33.410`)
- [CVE-2025-70811](CVE-2025/CVE-2025-708xx/CVE-2025-70811.json) (`2026-04-17T13:05:33.037`)
- [CVE-2026-35618](CVE-2026/CVE-2026-356xx/CVE-2026-35618.json) (`2026-04-17T12:20:03.500`)
- [CVE-2026-35622](CVE-2026/CVE-2026-356xx/CVE-2026-35622.json) (`2026-04-17T12:19:18.723`)
- [CVE-2026-35624](CVE-2026/CVE-2026-356xx/CVE-2026-35624.json) (`2026-04-17T12:18:26.953`)
- [CVE-2026-40253](CVE-2026/CVE-2026-402xx/CVE-2026-40253.json) (`2026-04-17T13:16:13.017`)
- [CVE-2026-40263](CVE-2026/CVE-2026-402xx/CVE-2026-40263.json) (`2026-04-17T13:16:13.437`)
- [CVE-2026-40308](CVE-2026/CVE-2026-403xx/CVE-2026-40308.json) (`2026-04-17T13:16:13.530`)
- [CVE-2026-40322](CVE-2026/CVE-2026-403xx/CVE-2026-40322.json) (`2026-04-17T13:16:13.643`)
- [CVE-2026-40900](CVE-2026/CVE-2026-409xx/CVE-2026-40900.json) (`2026-04-17T13:16:13.750`)
- [CVE-2026-4111](CVE-2026/CVE-2026-41xx/CVE-2026-4111.json) (`2026-04-17T12:16:32.843`)


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

## Bot Source Code

The source code running this repo is available here: [`nvd_json_bot`](https://github.com/fkie-cad/nvd_json_bot).

## Non-Endorsement Clause

This project uses and redistributes data from the NVD API but is not endorsed or certified by the NVD.