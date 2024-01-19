# edi-public-repo-test
**For testing and preparing a public repo for Maersk EDI resources.**

The resources of this repo will be organized according to following path model:

`
/<Product Type>/<Business Function>/<Business Process>/<Message Type>
`

Product Types and Business Functions will be shortened according to the Master Data below.
Message Type will be the different message types supported and resources related to the Message Type can be found in the corresponding folder.

## Master Data

### Product Types
| # | Identifier / Key | Description                  |
| - | :--------------: | ---------------------------- |
| 1 | air              | Air Transport                |
| 2 | eco              | E-Commerce/Omni-channel      |
| 3 | lan              | Landside Transport           |
| 4 | lcl              | LCL Transport                |
| 5 | oce              | Ocean Transport              |
| 6 | scm              | Supply Chain Management      |
| 7 | ter              | Terminals (APMT)             |
| 8 | wnd              | Warehousing and Distribution |

### Business Functions
| # | Identifier / Key | Description            |
| - | :--------------: | ---------------------- |
| 1 | com              | Commercial             |
| 2 | ops              | Operational            |
| 3 | fin              | Financial              |
| 4 | vis              | Visibility             |
