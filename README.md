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
2024-10-29T21:00:19.713996+00:00
```

### Most recent CVE Modification Timestamp synchronized with NVD

```plain
2024-10-29T20:59:57.227000+00:00
```

### Last Data Feed Release

Download and Changelog: [Click](https://github.com/fkie-cad/nvd-json-data-feeds/releases/latest)

```plain
2024-10-29T08:01:49.015410+00:00
```

### Total Number of included CVEs

```plain
267560
```

### CVEs added in the last Commit

Recently added CVEs: `0`



### CVEs modified in the last Commit

Recently modified CVEs: `132`

- [CVE-2024-48655](CVE-2024/CVE-2024-486xx/CVE-2024-48655.json) (`2024-10-29T20:35:33.500`)
- [CVE-2024-48700](CVE-2024/CVE-2024-487xx/CVE-2024-48700.json) (`2024-10-29T19:35:24.643`)
- [CVE-2024-48743](CVE-2024/CVE-2024-487xx/CVE-2024-48743.json) (`2024-10-29T19:35:25.777`)
- [CVE-2024-48825](CVE-2024/CVE-2024-488xx/CVE-2024-48825.json) (`2024-10-29T19:35:26.547`)
- [CVE-2024-48826](CVE-2024/CVE-2024-488xx/CVE-2024-48826.json) (`2024-10-29T19:35:27.303`)
- [CVE-2024-4887](CVE-2024/CVE-2024-48xx/CVE-2024-4887.json) (`2024-10-29T19:52:44.863`)
- [CVE-2024-51075](CVE-2024/CVE-2024-510xx/CVE-2024-51075.json) (`2024-10-29T20:35:35.130`)
- [CVE-2024-51076](CVE-2024/CVE-2024-510xx/CVE-2024-51076.json) (`2024-10-29T20:35:35.890`)
- [CVE-2024-51180](CVE-2024/CVE-2024-511xx/CVE-2024-51180.json) (`2024-10-29T20:35:36.680`)
- [CVE-2024-51181](CVE-2024/CVE-2024-511xx/CVE-2024-51181.json) (`2024-10-29T20:35:37.490`)
- [CVE-2024-51506](CVE-2024/CVE-2024-515xx/CVE-2024-51506.json) (`2024-10-29T19:35:28.723`)
- [CVE-2024-51507](CVE-2024/CVE-2024-515xx/CVE-2024-51507.json) (`2024-10-29T19:35:29.513`)
- [CVE-2024-51508](CVE-2024/CVE-2024-515xx/CVE-2024-51508.json) (`2024-10-29T19:35:30.513`)
- [CVE-2024-51509](CVE-2024/CVE-2024-515xx/CVE-2024-51509.json) (`2024-10-29T19:35:31.290`)
- [CVE-2024-5425](CVE-2024/CVE-2024-54xx/CVE-2024-5425.json) (`2024-10-29T19:49:44.357`)
- [CVE-2024-5607](CVE-2024/CVE-2024-56xx/CVE-2024-5607.json) (`2024-10-29T20:08:50.497`)
- [CVE-2024-6150](CVE-2024/CVE-2024-61xx/CVE-2024-6150.json) (`2024-10-29T19:35:32.787`)
- [CVE-2024-6600](CVE-2024/CVE-2024-66xx/CVE-2024-6600.json) (`2024-10-29T20:35:38.603`)
- [CVE-2024-6614](CVE-2024/CVE-2024-66xx/CVE-2024-6614.json) (`2024-10-29T20:35:39.450`)
- [CVE-2024-6760](CVE-2024/CVE-2024-67xx/CVE-2024-6760.json) (`2024-10-29T20:35:40.280`)
- [CVE-2024-7004](CVE-2024/CVE-2024-70xx/CVE-2024-7004.json) (`2024-10-29T20:35:41.127`)
- [CVE-2024-7208](CVE-2024/CVE-2024-72xx/CVE-2024-7208.json) (`2024-10-29T19:35:33.770`)
- [CVE-2024-7255](CVE-2024/CVE-2024-72xx/CVE-2024-7255.json) (`2024-10-29T20:35:42.023`)
- [CVE-2024-7518](CVE-2024/CVE-2024-75xx/CVE-2024-7518.json) (`2024-10-29T20:35:43.097`)
- [CVE-2024-7978](CVE-2024/CVE-2024-79xx/CVE-2024-7978.json) (`2024-10-29T20:35:44.730`)


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