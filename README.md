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
2024-12-04T15:02:14.826318+00:00
```

### Most recent CVE Modification Timestamp synchronized with NVD

```plain
2024-12-04T14:57:13.823000+00:00
```

### Last Data Feed Release

Download and Changelog: [Click](https://github.com/fkie-cad/nvd-json-data-feeds/releases/latest)

```plain
2024-12-04T01:00:10.096689+00:00
```

### Total Number of included CVEs

```plain
272101
```

### CVEs added in the last Commit

Recently added CVEs: `5`

- [CVE-2024-11935](CVE-2024/CVE-2024-119xx/CVE-2024-11935.json) (`2024-12-04T13:15:05.910`)
- [CVE-2024-12138](CVE-2024/CVE-2024-121xx/CVE-2024-12138.json) (`2024-12-04T14:15:19.413`)
- [CVE-2024-51465](CVE-2024/CVE-2024-514xx/CVE-2024-51465.json) (`2024-12-04T14:15:20.223`)
- [CVE-2024-53125](CVE-2024/CVE-2024-531xx/CVE-2024-53125.json) (`2024-12-04T14:15:20.460`)
- [CVE-2024-7488](CVE-2024/CVE-2024-74xx/CVE-2024-7488.json) (`2024-12-04T14:15:21.000`)


### CVEs modified in the last Commit

Recently modified CVEs: `23`

- [CVE-2023-40735](CVE-2023/CVE-2023-407xx/CVE-2023-40735.json) (`2024-12-04T13:15:05.183`)
- [CVE-2024-30271](CVE-2024/CVE-2024-302xx/CVE-2024-30271.json) (`2024-12-04T14:57:13.823`)
- [CVE-2024-30272](CVE-2024/CVE-2024-302xx/CVE-2024-30272.json) (`2024-12-04T14:45:39.650`)
- [CVE-2024-30273](CVE-2024/CVE-2024-302xx/CVE-2024-30273.json) (`2024-12-04T14:35:16.303`)
- [CVE-2024-52277](CVE-2024/CVE-2024-522xx/CVE-2024-52277.json) (`2024-12-04T13:15:06.080`)
- [CVE-2024-8812](CVE-2024/CVE-2024-88xx/CVE-2024-8812.json) (`2024-12-04T14:56:07.463`)
- [CVE-2024-8813](CVE-2024/CVE-2024-88xx/CVE-2024-8813.json) (`2024-12-04T14:56:03.620`)
- [CVE-2024-8814](CVE-2024/CVE-2024-88xx/CVE-2024-8814.json) (`2024-12-04T14:55:59.677`)
- [CVE-2024-8815](CVE-2024/CVE-2024-88xx/CVE-2024-8815.json) (`2024-12-04T14:55:55.787`)
- [CVE-2024-8816](CVE-2024/CVE-2024-88xx/CVE-2024-8816.json) (`2024-12-04T14:55:51.693`)
- [CVE-2024-8817](CVE-2024/CVE-2024-88xx/CVE-2024-8817.json) (`2024-12-04T14:55:21.647`)
- [CVE-2024-8818](CVE-2024/CVE-2024-88xx/CVE-2024-8818.json) (`2024-12-04T14:55:10.590`)
- [CVE-2024-8819](CVE-2024/CVE-2024-88xx/CVE-2024-8819.json) (`2024-12-04T14:50:28.667`)
- [CVE-2024-8820](CVE-2024/CVE-2024-88xx/CVE-2024-8820.json) (`2024-12-04T14:49:53.280`)
- [CVE-2024-8821](CVE-2024/CVE-2024-88xx/CVE-2024-8821.json) (`2024-12-04T14:48:52.033`)
- [CVE-2024-8822](CVE-2024/CVE-2024-88xx/CVE-2024-8822.json) (`2024-12-04T14:47:30.647`)
- [CVE-2024-8823](CVE-2024/CVE-2024-88xx/CVE-2024-8823.json) (`2024-12-04T14:45:59.687`)
- [CVE-2024-8824](CVE-2024/CVE-2024-88xx/CVE-2024-8824.json) (`2024-12-04T14:44:31.470`)
- [CVE-2024-8839](CVE-2024/CVE-2024-88xx/CVE-2024-8839.json) (`2024-12-04T14:43:09.680`)
- [CVE-2024-8840](CVE-2024/CVE-2024-88xx/CVE-2024-8840.json) (`2024-12-04T14:42:12.897`)
- [CVE-2024-8841](CVE-2024/CVE-2024-88xx/CVE-2024-8841.json) (`2024-12-04T14:41:07.097`)
- [CVE-2024-8842](CVE-2024/CVE-2024-88xx/CVE-2024-8842.json) (`2024-12-04T14:38:40.640`)
- [CVE-2024-8962](CVE-2024/CVE-2024-89xx/CVE-2024-8962.json) (`2024-12-04T12:15:20.913`)


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