def Message1 = 'Hey World 1'
def Message2 = 'Hey World 2'

node {
   sh: 'env'
   stage 'Stage 1'
   echo "$Message1 ${env.BRANCH_NAME}"
   stage 'Stage 2'
   echo "$Message2 ${env.WORKSPACE}"
}
