scala_library(name='scala',
  provides = scala_artifact(
    org = 'com.twitter.inject',
    name = 'inject-app',
    repo = artifactory,
  ),
  dependencies=[
    '3rdparty/jvm/com/fasterxml/jackson/core:jackson-annotations',
    '3rdparty/jvm/com/google/inject:guice',
    '3rdparty/jvm/joda-time:joda-time',
    '3rdparty:joda-convert',
    'finatra/inject/inject-core',
    'util/util-app',
  ],
  sources=rglobs('*.scala'),
  java_sources=[
    'finatra/inject/inject-app/src/main/java',
  ],
)
