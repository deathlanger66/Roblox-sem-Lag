# GAME HUB 2.0 - COMANDOS ROBLOX A13

# MODO DESEMPENHO / RESOLUÇÃO BAIXA
wm size 720x1600
wm density 240
settings put global window_animation_scale 0.5
settings put global transition_animation_scale 0.5
settings put global animator_duration_scale 0.5

# ABRIR ROBLOX
monkey -p com.roblox.client 1

# MODO NORMAL / RESTAURAR
wm size reset
wm density reset
settings put global window_animation_scale 1
settings put global transition_animation_scale 1
settings put global animator_duration_scale 1

# LIMPAR CACHE DO ROBLOX
pm trim-caches 999G

# FORÇAR PARAR ROBLOX
am force-stop com.roblox.client
