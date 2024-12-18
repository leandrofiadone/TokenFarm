# TokenFarm - Sistema de Staking Descentralizado

## Resumen
TokenFarm es una DApp (aplicación descentralizada) que permite a usuarios stakear tokens LP para ganar recompensas en DAppTokens. El sistema incluye funcionalidades para stakear, reclamar recompensas y retirar tokens, con un mecanismo de tarifas incluido.

## Funcionalidades Principales
- Staking de tokens LP
- Sistema de recompensas basado en tiempo y cantidad stakeada
- Reclamación de recompensas con tarifa
- Retiro completo de tokens y recompensas

## Contratos
1. **DAppToken**: Token ERC20 para recompensas
2. **LPToken**: Token ERC20 simulado para staking
3. **TokenFarm**: Contrato principal que gestiona el sistema

## Desarrollo y Pruebas
- Requiere Node.js y npm
- Utiliza Hardhat como entorno de desarrollo
- Incluye tests completos para todas las funcionalidades

## Comandos Principales
```bash
npm install              # Instalar dependencias
npx hardhat compile     # Compilar contratos
npx hardhat test        # Ejecutar tests
npx hardhat run scripts/deploy.ts  # Desplegar contratos