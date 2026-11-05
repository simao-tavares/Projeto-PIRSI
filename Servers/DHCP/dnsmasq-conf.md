interface=enp0s25
bind-interfaces
listen-address=10.10.11.180
port=0

# ---------- ÁGUEDA ----------

# Guests_AG
dhcp-range=set:GUESTS_AG,10.10.11.1,10.10.11.59,255.255.255.192,24h
dhcp-option=tag:GUESTS_AG,option:router,10.10.11.62

# Desenvolvimento_AG
dhcp-range=set:DESENVOLVIMENTO_AG,10.10.11.65,10.10.11.91,255.255.255.224,24h
dhcp-option=tag:DESENVOLVIMENTO_AG,option:router,10.10.11.94

# Publicidade_AG
dhcp-range=set:PUBLICIDADE_AG,10.10.11.97,10.10.11.123,255.255.255.224,24h
dhcp-option=tag:PUBLICIDADE_AG,option:router,10.10.11.126

# Guias_Animadores_AG
dhcp-range=set:GUIAS_ANIMADORES_AG,10.10.11.129,10.10.11.155,255.255.255.224,24h
dhcp-option=tag:GUIAS_ANIMADORES_AG,option:router,10.10.11.158

# Admin_AG
dhcp-range=set:ADMIN_AG,10.10.11.161,10.10.11.171,255.255.255.240,24h
dhcp-option=tag:ADMIN_AG,option:router,10.10.11.174


# ---------- AVEIRO ----------

# Guests_AV
dhcp-range=set:GUESTS_AV,10.10.12.1,10.10.12.59,255.255.255.192,24h
dhcp-option=tag:GUESTS_AV,option:router,10.10.12.62

# VoIP_AV
dhcp-range=set:VOIP_AV,10.10.12.65,10.10.12.123,255.255.255.192,24h
dhcp-option=tag:VOIP_AV,option:router,10.10.12.126

# Guias_Animadores_AV
dhcp-range=set:GUIAS_ANIMADORES_AV,10.10.12.129,10.10.12.155,255.255.255.224,24h
dhcp-option=tag:GUIAS_ANIMADORES_AV,option:router,10.10.12.158

# Financeiro_AV
dhcp-range=set:FINANCEIRO_AV,10.10.12.161,10.10.12.171,255.255.255.240,24h
dhcp-option=tag:FINANCEIRO_AV,option:router,10.10.12.174

# Admin_AV
dhcp-range=set:ADMIN_AV,10.10.12.177,10.10.12.187,255.255.255.240,24h
dhcp-option=tag:ADMIN_AV,option:router,10.10.12.190


# ---------- AZEMÉIS ----------

# Guests_AZ
dhcp-range=set:GUESTS_AZ,10.10.13.1,10.10.13.59,255.255.255.192,24h
dhcp-option=tag:GUESTS_AZ,option:router,10.10.13.62

# Desenvolvimento_AZ
dhcp-range=set:DESENVOLVIMENTO_AZ,10.10.13.65,10.10.13.91,255.255.255.224,24h
dhcp-option=tag:DESENVOLVIMENTO_AZ,option:router,10.10.13.94

# Recursos_Humanos_AZ
dhcp-range=set:RECURSOS_HUMANOS_AZ,10.10.13.97,10.10.13.107,255.255.255.240,24h
dhcp-option=tag:RECURSOS_HUMANOS_AZ,option:router,10.10.13.110