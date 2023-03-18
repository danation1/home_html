;;
;; Domain:     a3world1.com.
;; Exported:   2023-02-26 14:00:36
;;
;; This file is intended for use for informational and archival
;; purposes ONLY and MUST be edited before use on a production
;; DNS server.  In particular, you must:
;;   -- update the SOA record with the correct authoritative name server
;;   -- update the SOA record with the contact e-mail address information
;;   -- update the NS record(s) with the authoritative name servers for this domain.
;;
;; For further information, please consult the BIND documentation
;; located on the following website:
;;
;; http://www.isc.org/
;;
;; And RFC 1035:
;;
;; http://www.ietf.org/rfc/rfc1035.txt
;;
;; Please note that we do NOT offer technical support for any use
;; of this zone data, the BIND name server, or any other third-party
;; DNS software.
;;
;; Use at your own risk.
;; SOA Record
a3world1.com	3600	IN	SOA	ernest.ns.cloudflare.com dns.cloudflare.com 2042908663 10000 2400 604800 3600

;; NS Records
a3world1.com.	86400	IN	NS	ernest.ns.cloudflare.com.
a3world1.com.	86400	IN	NS	molly.ns.cloudflare.com.

;; CNAME Records
www.a3world1.com.	1	IN	CNAME	danation.icloud. ; Check it

;; MX Records
www.a3world1.com.	86400	IN	MX	10 donation.icloud. ; Love you all

;; TXT Records
a3world1.com.	1	IN	TXT	"v=spf1 -all"
a3world1.com.	3600	IN	TXT	"apple-domain=yX5SIVNBoeGvSaQU"
_dmarc.a3world1.com.	1	IN	TXT	"v=DMARC1; p=none; rua=mailto:theplentycode6@gmail.com"
_dmarc.a3world1.com.	1	IN	TXT	"v=DMARC1; p=reject; sp=reject; adkim=s; aspf=s; rua=mailto:theplentycode6@gmail.com,mailto:theplentycode12@gmail.com"
*._domainkey.a3world1.com.	1	IN	TXT	"v=DKIM1; p="
