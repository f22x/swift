add_swift_library(swiftIntents IS_SDK_OVERLAY
  Intents.swift
  INBooleanResolutionResult.swift
  INDoubleResolutionResult.swift
  INIntegerResolutionResult.swift
  INListRideOptionsIntentResponse.swift
  INRequestRideIntent.swift
  INSetClimateSettingsInCarIntent.swift
  INSetDefrosterSettingsInCarIntent.swift
  INSetRadioStationIntent.swift
  INSetSeatTemperatureInCarIntent.swift
  INSearchForPhotosIntentResponse.swift
  INStartPhotoPlaybackIntentResponse.swift
  INStartWorkoutIntent.swift

  TARGET_SDKS OSX IOS IOS_SIMULATOR
  SWIFT_MODULE_DEPENDS Foundation CoreLocation
  SWIFT_MODULE_DEPENDS_OSX AppKit
  SWIFT_MODULE_DEPENDS_IOS UIKit
  FRAMEWORK_DEPENDS_WEAK Intents)
