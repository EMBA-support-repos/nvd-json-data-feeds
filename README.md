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
2025-02-05T15:01:41.621690+00:00
```

### Most recent CVE Modification Timestamp synchronized with NVD

```plain
2025-02-05T15:00:11.080000+00:00
```

### Last Data Feed Release

Download and Changelog: [Click](https://github.com/fkie-cad/nvd-json-data-feeds/releases/latest)

```plain
2025-02-05T01:00:04.367301+00:00
```

### Total Number of included CVEs

```plain
280122
```

### CVEs added in the last Commit

Recently added CVEs: `3`

- [CVE-2024-2878](CVE-2024/CVE-2024-28xx/CVE-2024-2878.json) (`2025-02-05T13:15:22.523`)
- [CVE-2024-9097](CVE-2024/CVE-2024-90xx/CVE-2024-9097.json) (`2025-02-05T13:15:23.237`)
- [CVE-2025-21117](CVE-2025/CVE-2025-211xx/CVE-2025-21117.json) (`2025-02-05T14:15:27.417`)


### CVEs modified in the last Commit

Recently modified CVEs: `77`

- [CVE-2024-38413](CVE-2024/CVE-2024-384xx/CVE-2024-38413.json) (`2025-02-05T13:58:37.347`)
- [CVE-2024-38414](CVE-2024/CVE-2024-384xx/CVE-2024-38414.json) (`2025-02-05T13:58:27.387`)
- [CVE-2024-38416](CVE-2024/CVE-2024-384xx/CVE-2024-38416.json) (`2025-02-05T13:58:16.960`)
- [CVE-2024-38417](CVE-2024/CVE-2024-384xx/CVE-2024-38417.json) (`2025-02-05T13:58:05.770`)
- [CVE-2024-38418](CVE-2024/CVE-2024-384xx/CVE-2024-38418.json) (`2025-02-05T13:57:33.277`)
- [CVE-2024-38420](CVE-2024/CVE-2024-384xx/CVE-2024-38420.json) (`2025-02-05T13:56:27.703`)
- [CVE-2024-3869](CVE-2024/CVE-2024-38xx/CVE-2024-3869.json) (`2025-02-05T14:42:53.307`)
- [CVE-2024-4370](CVE-2024/CVE-2024-43xx/CVE-2024-4370.json) (`2025-02-05T14:47:17.857`)
- [CVE-2024-45454](CVE-2024/CVE-2024-454xx/CVE-2024-45454.json) (`2025-02-05T15:00:11.080`)
- [CVE-2024-45560](CVE-2024/CVE-2024-455xx/CVE-2024-45560.json) (`2025-02-05T13:56:20.097`)
- [CVE-2024-45561](CVE-2024/CVE-2024-455xx/CVE-2024-45561.json) (`2025-02-05T13:55:59.953`)
- [CVE-2024-45569](CVE-2024/CVE-2024-455xx/CVE-2024-45569.json) (`2025-02-05T13:55:49.460`)
- [CVE-2024-47332](CVE-2024/CVE-2024-473xx/CVE-2024-47332.json) (`2025-02-05T14:59:27.147`)
- [CVE-2024-49649](CVE-2024/CVE-2024-496xx/CVE-2024-49649.json) (`2025-02-05T14:30:52.037`)
- [CVE-2024-49685](CVE-2024/CVE-2024-496xx/CVE-2024-49685.json) (`2025-02-05T14:51:00.297`)
- [CVE-2024-50433](CVE-2024/CVE-2024-504xx/CVE-2024-50433.json) (`2025-02-05T14:50:13.567`)
- [CVE-2024-5147](CVE-2024/CVE-2024-51xx/CVE-2024-5147.json) (`2025-02-05T14:52:39.890`)
- [CVE-2024-52471](CVE-2024/CVE-2024-524xx/CVE-2024-52471.json) (`2025-02-05T14:55:10.440`)
- [CVE-2024-53786](CVE-2024/CVE-2024-537xx/CVE-2024-53786.json) (`2025-02-05T14:46:20.417`)
- [CVE-2024-53823](CVE-2024/CVE-2024-538xx/CVE-2024-53823.json) (`2025-02-05T14:40:24.877`)
- [CVE-2024-54367](CVE-2024/CVE-2024-543xx/CVE-2024-54367.json) (`2025-02-05T14:28:44.787`)
- [CVE-2024-5646](CVE-2024/CVE-2024-56xx/CVE-2024-5646.json) (`2025-02-05T14:47:15.223`)
- [CVE-2024-7389](CVE-2024/CVE-2024-73xx/CVE-2024-7389.json) (`2025-02-05T14:59:01.993`)
- [CVE-2024-8442](CVE-2024/CVE-2024-84xx/CVE-2024-8442.json) (`2025-02-05T14:52:03.700`)
- [CVE-2025-22752](CVE-2025/CVE-2025-227xx/CVE-2025-22752.json) (`2025-02-05T14:33:42.787`)


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