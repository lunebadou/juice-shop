nœud {
  étape('SCM') {
    caisse scm
  }
  étape('Analyse SonarQube') {
    def scannerHome = outil 'SonarQubeScanner';
    avecSonarQubeEnv() {
      sh "${scannerHome}/bin/sonar-scanner"
    }
  }
}
