# Work Details

We need a local extension for Direccion Nacional de Vialidad Argentina (DNV) in which we can define specific information about the contracting process such as:

* Global status
* Type of management

This extension will allow DNV to show more precise information about the general process, and is needed since it can not be inferred from the OCDS fields. By incorporating global status and type of management, DNV will bring users the possibility to use it as filters.

## Worked example
The "Work Details" extension will be a general field, which mean that will be at the same level as buyer or planning

```json
{
  "workDetails": {
        "status": {
            "id" : "2",
            "description" : "Finalizada"
        },
        "type": {
            "id" : "5",
            "description" : "Mantenimiento"
        }
    }
}

```
