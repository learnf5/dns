# dns
Repo for DNS SDT course

SCF files are difference files, not a complete big-ip configration set.
Use the tmsh command to merge the given scf into the base lab configuration
tmsh load sys config merge file create_dns_listener.scf

SCF file names follow the captured state of the previous lab. Example, create_dns_listener.scf contains the big-ip configuration and local traffic objects created in the DNS-C1C04-ProvBigip lab.
Notice that some labs start from a common configuration, using configure_wideip.scf for multiple lab starting points.

| Lab Name | Archive File |
| --- | --- |
| DNS-C1A01-Tmsh | cfg_w_tmsh.scf |
| DNS-C1C04-ProvBigip | *none* |
| DNS-C1C06-LoadBalDns | create_dns_listener.scf |
| DNS-C1C08-ResFromCache | load_balance_dns_queries.scf |
| DNS-C1C10-DnsExpress | resolve_dsn_queries_cache.scf |
| DNS-C1C12-SimpleWideIp | implement_dns_express.scf |
| DNS-C1C14-ResUsingRem | configure_simple_wideip.scf |
| DNS-C2B05-iQuery | create_dns_listener.scf |
| DNS-C2B10-WideIp | add_non_f5_server.scf |
| DNS-C2C03-ObjStateCh | configure_wideip.scf |
| DNS-C3A03-LdnsProbe | configure_wideip.scf |
| DNS-C3B08-DynPersistLB | configure_wideip.scf |
| DNS-C3B09-RatioLB | configure_wideip.scf |
| DNS-C3C03-ManResume | test_global_availability_lb.scf |
| DNS-C3D06-MonDnsRes | test_topology_lb.scf |
| DNS-C3E02-DnsSec | configure_wideip.scf |
| DNS-C3E04-WideIpPool | test_global_availability_lb.scf |
| DNS-C3E07-SyncGrp | configure_wideip.scf |
