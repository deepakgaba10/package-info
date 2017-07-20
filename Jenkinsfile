pipeline {
    System.getProperties().put("proxySet", "true"); System.getProperties().put("http.proxyHost", "ukproxy.bip.uk.fid-intl.com"); System.getProperties().put("http.proxyPort", "8000"); System.getProperties().put("https.proxyHost", "ukproxy.bip.uk.fid-intl.com"); System.getProperties().put("https.proxyPort", "8000"); System.getProperties().put("http.nonProxyHosts", "*.domainy.local|*.domainx.local");
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
