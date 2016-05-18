def Message1 = 'Hey World 1'
def Message2 = 'Hey World 2'

node {
   stage 'Stage 1'
   sh: 'env'
   echo "$Message1 ${env.BRANCH_NAME}"
   stage 'Stage 2'
   echo "$Message2 ${env.WORKSPACE}"
}
