
# Comment les erreurs entre AgentConnect et le Fournisseur de Services sont-elles gérées?

En tant qu'OpenID Connect provider, AgentConnect peut renvoyer toutes sortes d'erreurs à une application cliente. Pour ce faire, AgentConnect passe par le mécanisme de retour d'erreurs d'un fournisseur d'identité openid connect tel que décrit dans la norme ( http://openid.net/specs/openid-connect-core-1_0.html#AuthError, en particulier les sections 3.1.2.6 (authentification), 3.1.3.4 (jeton d'accès), 5.3.3 (service d'informations utilisateur) )