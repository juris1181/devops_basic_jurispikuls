# DevOps repozitorijs
Juris Pikuls DevOps repozitorijs pamati iesācējiem

14. Katram failam, hash fails ir vienāds dažādās mapēs.
Git lokāli un githubā hash ir vienāds, jo tas tiek vienāds izveidots pie katra commita veikšanas.
Vienam commitam gan git, gan github ir vienāds hash



16. Izmaiņas tika veiktas daudz un dažādas, sākot ar versiju update, changelog update, līdz pat ssh support over http proxy config izmaiņām.

17. Daudz: piemēram -
Jurchix-PC@Jurchix MINGW32 ~/Desktop/git_repos/terraform (main)
$ git log --grep="Laura Pacilio"
commit 4e95b24022e17189dacf54f5742359cc24cbc5df
Author: James Bardin <j.bardin@gmail.com>
Date:   Tue Apr 26 18:17:52 2022 -0400

    Update website/docs/language/meta-arguments/lifecycle.mdx

    Co-authored-by: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>

commit 6c15cab211097820d809f64076ad1673d1567dcb
Author: James Bardin <j.bardin@gmail.com>
Date:   Tue Apr 26 18:17:46 2022 -0400

    Update website/docs/language/meta-arguments/lifecycle.mdx

    Co-authored-by: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>

commit 840a7437c2097c7e77a8297525ec7e2cd6898021
Author: James Bardin <j.bardin@gmail.com>
Date:   Tue Apr 26 18:17:41 2022 -0400

    Update website/docs/language/meta-arguments/lifecycle.mdx

    Co-authored-by: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
	
	
	18. Septembri ir veikta izmaiņa:
	commit fa4c590f515a9a5ae40d9122b325a803be975f0c
Author: Yves Peter <ypwebstuff@gmail.com>
Date:   Fri Sep 3 08:23:17 2021 +0200

    Apply suggestions from code review

    Co-authored-by: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>

	
	19. Laura pēdējo izmaiņu veikusi kopā ar sebastianu 26.aprili plkst. 18:17:58
	
	20. Iespējams apvienoti faili ar 16.apriļa failu ???
	$ git log --since=2021-04-20 --until=2021-04-21
commit f8493bf5cd78bc2a723f5ddc6f6bceb0e08813ea
Author: James Bardin <j.bardin@gmail.com>
Date:   Fri Apr 16 17:11:27 2021 -0400

    update hcl

    update to v2.10.0

commit d15f7394a19f8f4d604b632df54c1d0cc0c9cc85
Merge: fabdf0bea 7f571b5eb
Author: James Bardin <j.bardin@gmail.com>
Date:   Tue Apr 20 16:25:34 2021 -0400

    Merge pull request #28457 from hashicorp/jbardin/provisioner-null-checks

    additional null checks in provisioners

commit 7f571b5ebb76111a2c671ac0c2212379cc676bcd
Author: James Bardin <j.bardin@gmail.com>
Date:   Tue Apr 20 12:31:32 2021 -0400

    additional null checks in provisioners

    Now that provisioners for directly with the plugin API and cty data
    types, we need to add a few null checks to catch invalid input that
    would have otherwise been masked by the legacy SDK.

Jurchix-PC@Jurchix MINGW32 ~/Desktop/git_repos/terraform (main)
$ git cat-file -p ^C

Jurchix-PC@Jurchix MINGW32 ~/Desktop/git_repos/terraform (main)
$ git cat-file -p d15f7394a19f8f4d604b632df54c1d0cc0c9cc85
tree 7befe001e5102b09638f5a0fd07bd20ecc69f834
parent fabdf0bea1fa2bf6a9d56cc3ea0f28242bf5e812
parent 7f571b5ebb76111a2c671ac0c2212379cc676bcd
author James Bardin <j.bardin@gmail.com> 1618950334 -0400
committer GitHub <noreply@github.com> 1618950334 -0400
gpgsig -----BEGIN PGP SIGNATURE-----

 wsBcBAABCAAQBQJgfzi+CRBK7hj4Ov3rIwAAM3gIALMX0nFZtf4y0mWb+mm7CyKI
 2p7SFVvxocj5AZf86oN4aBoCyI1yvoNhPHRA/OVA4pmLZHrDVOehk8DMFl/Xwsz3
 wHAUSk1LpIaChlD4IfRnae1y3PMTMGoOvXxZPEikpmCCci8qMgzvO0AS4IevB7G4
 RjdoS3Kw2wO3savAY5CKcMQUKonfnscgPRm0cqBoGWo9t3JITpFbDLWBoVnyB/lb
 enOQQv9N3ElX/0u0Qa5uUIIaBjrAFFlyU3NrLzFdf/Gwfpw28NOKNqfOJl3GA+qu
 4vQB6eXgvIo7aXRvTX6RKXkHHqD/QRoREPymubfkY7RD+Kf9DGwepyfRPD+lbuQ=
 =6kgo
 -----END PGP SIGNATURE-----


Merge pull request #28457 from hashicorp/jbardin/provisioner-null-checks

additional null checks in provisioners



