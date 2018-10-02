node {

    checkout scm
    def branchName = env.BRANCH_NAME

    print "Loading branch: ${branchName}"

    if (branchName == "master") {
        load 'jenkinsFileMaster'
    } else if (branchName == "development") {
        load 'jenkinsFileDevelopment'
    }

}


