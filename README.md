# VersionSchema
Project to define a schema for declaring version string formats and semantic meaning therein.

## What's this about?
VersionSchema is all about defining what the [VersionMeta](https://github.com/versionschema/versionmeta) tag points to. The goal is to define a domain specific language that facilitates machine reasoning over version tags and keeps humans in the loop as well.  Initially, this is probably one or more of XML, JSON or YAML with a data format defined by XSD or whatever stands in for one for YAML and JSON.  Much is yet to be determined here.  Perhaps EBNF is the right way to go?

# Looking for stakeholders
- Anyone who owns an existing, documented version scheme.
- Anyone who owns or is a major influencer/contributor to software packaging/publishing tools.
- Anyone with any tool that reads and acts on any kind of version string.
