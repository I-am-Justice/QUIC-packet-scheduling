#Steps for development of QUIC scheduler


#Steps to be taken during Comaparion experiments

Steps
1) Build Chromium on Linux: Installed Chromium 
2) Playing with QUIC: Follow this for quic_server and quic_client: https://www.chromium.org/quic/playing-with-quic
3) Linux Cert Management: Did this after making a folder for <my_website_name>.com in the quic_respons_cache_dir
4) Added the cert files in the browser
5) Edited the /etc/hosts as Gregory mentioned here
6) Pointed the quic_respons_cache_dir to a dummy website, and run it via QUIC.

#Source: Sushant Mongia 01/04/2017
https://groups.google.com/a/chromium.org/forum/#!searchin/proto-quic/Sushant$20Mongia/proto-quic/2nyLYC6JTBo/hvOkRmvoGwAJ
