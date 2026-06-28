# KessDB

KessDB is a proprietary embedded object-document database for .NET NativeAOT applications. It is designed around single-file `.kess` storage, dense Brotli-compressed chunks, generated POCO codecs, and fast typed reads without runtime reflection mapping.

This repository publishes the public KessDB product site and technical whitepaper.

Visit: https://kessdb.com/

## What KessDB Targets

KessDB is built for read-heavy software that ships structured data as an application asset: game definitions, rules, catalogs, pricing tables, feature packs, static reference models, and periodically refreshed edge data.

It focuses on compact local storage, predictable typed access, and NativeAOT-friendly generated code for applications that own their schema and want a lighter alternative to loose JSON, MessagePack blobs, SQLite tables, or service-backed reference data.

## Technical Highlights

- Embedded object-document storage for .NET and C#
- Single-file `.kess` database containers
- Brotli-compressed chunk storage
- Source-generated POCO codecs and typed views
- NativeAOT-oriented design with no runtime reflection mapping
- Zero-copy views over decompressed pooled buffers
- Single-writer, multi-reader storage model
- Validation, compaction, salvage, and benchmark smoke tooling

## Source Availability

KessDB source code is private and proprietary. This public repository exists to publish product information, technical positioning, and licensing context.

For product review, commercial licensing, acquisition diligence, or private technical access, contact the copyright owner through the public site.

## Rights

The website and whitepaper content are provided as a public technical overview. They are not open source and do not grant rights to use, copy, modify, redistribute, host, sell, sublicense, or create derivative works from KessDB or the website materials without written permission from the copyright owner.
