# BscProject-Membership
copir sur ton mur l id  de tta valis

# BscProject-Membership
# BscProject-Membership


COPIE  CE FICHIER DANS PHENIXMINER  start.bat



REM
REM Example bat file for starting PhoenixMiner.exe to mine ETH
REM

setx GPU_FORCE_64BIT_PTR 0
setx GPU_MAX_HEAP_SIZE 100
setx GPU_USE_SYNC_OBJECTS 1
setx GPU_MAX_ALLOC_PERCENT 100
setx GPU_SINGLE_ALLOC_PERCENT 100

REM IMPORTANT: Replace the ETH address with your own ETH wallet address in the -wal option (Rig001 is the name of the rig)
PhoenixMiner.exe -pool stratum+tcp://ethash.poolbinance.com:1800 -pool2 stratum+tcp://ethash.poolbinance.com:25 -wal 0x457147f9149B16A6A154e43194137d382086023e.taszipame2.001
pause

