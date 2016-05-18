env.Message1 = 'Hey World 1'
env.Message2 = 'Hey World 2'

node {
   stage 'Stage 1'
   echo '$Message1 $BRANCH_NAME'
   stage 'Stage 2'
   echo '$Message2 $env.WORKSPACE'
}
