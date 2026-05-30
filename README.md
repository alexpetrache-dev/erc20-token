# MyToken — ERC-20

Token ERC-20 completo implementado desde cero en Solidity (sin dependencias externas),
para demostrar comprension del estandar EIP-20.

## Caracteristicas

- Implementacion completa de EIP-20: `transfer`, `approve`, `transferFrom`, `balanceOf`, `allowance`.
- **Mint** controlado por el owner (`mint`).
- **Burn** por el propio holder (`burn`).
- Transferencia de propiedad (`transferOwnership`).
- Eventos `Transfer` y `Approval` segun estandar.
- Suministro inicial acuñado al deployer en el despliegue.

## Constructor

| Parametro      | Tipo    | Descripcion                                  |
|----------------|---------|----------------------------------------------|
| `_name`        | string  | Nombre del token (ej. "My Token")            |
| `_symbol`      | string  | Simbolo (ej. "MYT")                          |
| `initialSupply`| uint256 | Suministro inicial en unidades enteras       |

`decimals` es fijo en 18.

## Red

- Solidity `^0.8.24`
- Desplegado y verificado en **Base** mainnet.

## Licencia

MIT
