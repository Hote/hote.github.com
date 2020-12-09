 # MacOS error code
 ## MacOS error Troubleshooting skill
1. If error code was relative security, can use security command to see the detail
``` 
     #can use following command to get the detail
     $security error -67062
```
1. How to find some useful tools were belong to which packages
```
brew search --desc [tool]. (--desc: search in description)
```
1. How to modify resolution of external monitor when it clamis "out of range"
* In System Preferences=>Display
* switch to Arrangement tab
* click "option" key, you will see the right corner wording change from "Gather Windows" to "Detect Displays"
* Now you will be able to change the resolution



 
 
 
 
 ## Mac error code list
* error -67062 security exception
* error -32768 svTempDisable: Temporarily disable card but run primary init.
* error -32640 svDisabled: Reserve range -32640 to -32768 for Apple temp disables.
* error -32615 fontNotOutlineErr: bitmap font passed to routine that does outlines only
* error -23048 outOfMemory: Not enough memory is available to issue the needed DNR query or to build the DNR cache.
* error -23047 dnrErr: The domain name server has returned an error.
* error -23046 noAnsErr: None of the known name servers are responding.
* error -23045 authNameErr: The domain name does not exist.
* error -23044 noNameServer: No name server can be found for the specified name string.
* error -23043 noResultProc: No result procedure is passed to the address translation call when the resolver must be used to find the address.
* error -23042 cacheFault: The name specified cannot be found in the cache. The domain name resolver will now query the domain name server and return the answer in the callback procedure.
* error -23041 nameSyntaxErr: The <> field had a syntax error. The address was given in dot notation (that is, W.X.Y.Z) and did not conform to the syntax for an IP address.
* error -23037 ipRouteErr: No gateway available to manage routing of packets to off-network destinations.
* error -23036 ipNoFragMemErr: Insufficient internal driver buffers available to fragment this packet on send.
* error -23035 icmpEchoTimeoutErr: The icmp echo packet was not responded to in the indicated timeout period.
* error -23033 ipDestDeadErr: The destination host is not responding to address resolution requests.
* error -23032 ipDontFragErr: The pack is too large to send without fragmenting and the Don't Fragment flag is set.
* error -23017 duplicateSocket: A stream is already open using the local UDP port or a TCP connection already exists between the local IP address and TCP port, and the specified remote IP address and TCP port.
* error -23016 commandTimeout: The specified command action was not completed in the specified time period.
* error -23015 openFailed: The connection came halfway up and then failed.
* error -23014 invalidWDS: The WDS pointer was 0 (nil).
* error -23014 invalidRDS: The RDS refers to receive buffers not owned by the user.
* error -23013 invalidBufPtr: The receive buffer area pointer is 0 (nil).
* error -23012 connectionTerminated: The TCP connection was broken; the reason will be given a terminate ASR.
* error -23011 streamAlreadyOpen: An open stream is already using the receive buffer area.
* error -23010 invalidStreamPtr: The specified TCP or UDP stream is not open.
* error -23009 insufficientResources: 64 TCP or UDP streams are already open.
* error -23008 connectionDoesntExist: The TCP stream has no open connection.
* error -23007 connectionExists: The TCP or UDP stream already has an open connection.
* error -23006 invalidLength: The total amount of data described by the WDS was either 0 or greater than 65,535 bytes.
* error -23005 connectionClosing: A TCPClose command was already issued so there is no more data to send on this connection.
* error -23004 ipBadAddr: Error in getting an address from a server or the address is already in use by another machine.
* error -23003 ipLoadErr: Not enough room in the application heap (Macintosh 512K enhanced only)
* error -23002 ipNoCnfgErr: A configuration resource is missing.
* error -23001 ipBadCnfgErr: The manually set address is configured improperly.
* error -23000 ipBadLapErr: Unable to initialize the local network handler.
* error -20002 invalidIndexErr: The recordIndex parameter is not valid.
* error -20001 recordDataTooBigErr: The record data is bigger than buffer size (1024 bytes).
* error -20000 unknownInsertModeErr: There is no such an insert mode.
* error -13005 pmRecvEndErr: during receive pmgr did not finish hs configured for this connection
* error -13004 pmRecvStartErr: during receive pmgr did not start hs
* error -13003 pmSendEndErr: during send pmgr did not finish hs
* error -13002 pmSendStartErr: during send pmgr did not start hs
* error -13001 pmReplyTOErr: Timed out waiting for reply
* error -13000 pmBusyErr: Power Mgr never ready to start handshake
* error -11005 pictureDataErr: the picture data was invalid
* error -11004 colorsRequestedErr: the number of colors requested was illegal
* error -11003 cantLoadPickMethodErr: unable to load the custom pick proc
* error -11002 pictInfoVerbErr: the passed verb was invalid
* error -11001 pictInfoIDErr: the internal consistancy check for the PictInfoID is wrong
* error -11000 pictInfoVersionErr: wrong version of the PictInfo structure
* error -10115 telBadSampleRate: incompatible sample rate
* error -10114 telBadSWErr: Software not installed properly
* error -10113 telDetAlreadyOn: detection is already turned on
* error -10112 telAutoAnsNotOn: autoAnswer in not turned on
* error -10111 telValidateFailed: telValidate failed
* error -10110 telBadProcID: invalid procID
* error -10109 telDeviceNotFound: device not found
* error -10108 telBadCodeResource: code resource not found
* error -10107 telInitFailed: initialization failed
* error -10106 telNoCommFolder: CommunicationsExtensions Ä not found
* error -10103 telUnknownErr: unable to set config
* error -10102 telNoSuchTool: unable to find tool with name specified
* error -10101 telNoTools: unable to find any telephone tools
* error -10091 telBadFunction: bad msgCode specified
* error -10090 telPBErr: parameter block error bad format
* error -10082 telCANotDeflectable: CA not "deflectable"
* error -10081 telCANotRejectable: CA not "rejectable"
* error -10080 telCANotAcceptable: CA not "acceptable"
* error -10072 telTermNotOpen: terminal not opened via TELOpenTerm
* error -10071 telStillNeeded: terminal driver still needed by someone else
* error -10070 telAlreadyOpen: terminal already open
* error -10064 telNoCallbackRef: no call back reference was specified but is required
* error -10063 telDisplayModeNotSupp: display mode not supported by tool
* error -10062 telBadDisplayMode: bad display mode specified
* error -10061 telFwdTypeNotSupp: forward type not supported by tool
* error -10060 telDNTypeNotSupp: DN type not supported by tool
* error -10059 telBadRate: bad rate specified
* error -10058 telBadBearerType: bad bearerType specified
* error -10057 telBadSelect: unable to select or deselect DN
* error -10056 telBadParkID: bad park id specified
* error -10055 telBadPickupGroupID: bad pickup group ID specified
* error -10054 telBadFwdType: bad fwdType specified
* error -10053 telBadFeatureID: bad feature ID specified
* error -10052 telBadIntercomID: bad intercom ID specified
* error -10051 telBadPageID: bad page ID specified
* error -10050 telBadDNType: DN type invalid
* error -10047 telConfLimitExceeded: attempt to exceed switch conference limits
* error -10046 telCBErr: call back feature not set previously
* error -10045 telTransferRej: transfer request rejected
* error -10044 telTransferErr: transfer not prepared
* error -10043 telConfRej: conference request was rejected
* error -10042 telConfErr: conference was not prepared
* error -10041 telConfNoLimit: no limit was specified but required
* error -10040 telConfLimitErr: limit specified is too high for this configuration
* error -10033 telFeatNotSupp: feature program call not supported by this tool
* error -10032 telFeatActive: feature already active
* error -10031 telFeatNotAvail: feature subscribed but not available
* error -10030 telFeatNotSub: feature not subscribed
* error -10024 telDNDTypeNotSupp: DND type is not supported by this tool
* error -10023 telBadDNDType: bad DND type specified
* error -10022 telIntExtNotSupp: internal external type not supported by this tool
* error -10021 telBadIntExt: bad internal external error
* error -10020 telStateNotSupp: device state not supported by tool
* error -10019 telBadStateErr: bad device state specified
* error -10018 telIndexNotSupp: index not supported by this tool
* error -10017 telBadIndex: bad index specified
* error -10016 errAELocalOnly or telAPattNotSupp: alerting pattern not supported by tool
* error -10015 errAECantUndo or telBadAPattErr: bad alerting pattern specified
* error -10014 errAENotASingleObject or telVTypeNotSupp: volume type not supported by this tool
* error -10013 errAENoUserSelection or telBadVTypeErr: bad volume type error
* error -10012 errAENoSuchTransaction or telBadLevelErr: bad volume level setting
* error -10011 errAEInTransaction or telHTypeNotSupp: hook type not supported by this tool
* error -10010 errAECantHandleClass or telBadHTypeErr: bad hook type specified
* error -10009 errAECantSupplyType
* error -10008 errAENotAnElement or telNoOpenErr: unable to open terminal
* error -10007 errAEIndexTooLarge or telNoMemErr: no memory to allocate handle
* error -10006 errAEWriteDenied or telCAUnavail: a CA is not available
* error -10005 errAEReadDenied or telBadProcErr: bad msgProc specified
* error -10004 errAEPrivilegeError or telBadHandErr: bad handle specified
* error -10003 errAENotModifiable or telBadCAErr: TELCAHandle not found or invalid
* error -10002 errAEBadKeyForm or telBadDNErr: TELDNHandle not found or invalid
* error -10001 errAETypeError or telBadTermErr: invalid TELHandle or handle not found
* error -10000 errAEEventFailed
* error -9999 cannotMoveAttachedController
* error -9998 controllerHasFixedHeight
* error -9997 cannotSetWidthOfAttachedController
* error -9996 controllerBoundsNotExact
* error -9995 editingNotAllowed
* error -9994 badControllerHeight
* error -9408 deviceCantMeetRequest
* error -9407 seqGrabInfoNotAvailable
* error -9406 badSGChannel
* error -9405 couldntGetRequiredComponent
* error -9404 notEnoughDiskSpaceToGrab
* error -9403 notEnoughMemoryToGrab
* error -9402 cantDoThatInCurrentMode
* error -9401 grabTimeComplete
* error -9400 noDeviceForChannel
* error -8976 codecNothingToBlitErr
* error -8975 codecCantQueueErr
* error -8974 codecCantWhenErr
* error -8973 codecOpenErr
* error -8972 codecConditionErr
* error -8971 codecExtensionNotFoundErr
* error -8970 codecDataVersErr
* error -8969 codecBadDataErr
* error -8968 codecWouldOffscreenErr
* error -8967 codecAbortErr
* error -8966 codecSpoolErr
* error -8965 codecImageBufErr
* error -8964 codecScreenBufErr
* error -8963 codecSizeErr
* error -8962 codecUnimpErr
* error -8961 noCodecErr
* error -8960 codecErr
* error -6231 kDMMainDisplayCannotMoveErr: Trying to move main display (or a display mirrored to it) or kDMNoDeviceTableclothErr: obsolete
* error -6230 kDMDisplayAlreadyInstalledErr: Attempt to add an already installed display.
* error -6229 kDMDisplayNotFoundErr: Could not find item (will someday remove). or kDMNotFoundErr: Could not find item.
* error -6228 kDMDriverNotDisplayMgrAwareErr: Video Driver does not support display manager.
* error -6227 kDMSWNotInitializedErr: Required software not initialized (eg windowmanager or display mgr).
* error -6226 kSysSWTooOld: Missing critical pieces of System Software.
* error -6225 kDMMirroringNotOn: Returned by all calls that need mirroring to be on to do their thing.
* error -6224 kDMCantBlock: Mirroring is already on canÕt Block now (call DMUnMirror() first).
* error -6223 kDMMirroringBlocked: DMBlockMirroring() has been called.
* error -6222 kDMWrongNumberOfDisplays: Can only handle 2 displays for now.
* error -6221 kDMMirroringOnAlready: Returned by all calls that need mirroring to be off to do their thing.
* error -6220 kDMGenErr: Unexpected Error
* error -5553 gestaltLocationErr: gestalt function ptr wasn't in sysheap
* error -5552 gestaltDupSelectorErr: tried to add an entry that already existed
* error -5551 gestaltUndefSelectorErr: undefined selector was passed to Gestalt
* error -5550 gestaltUnknownErr: value returned if Gestalt doesn't know the answer
* error -5502 envVersTooBig: Version bigger than call can handle
* error -5501 envBadVers: Version non-positive
* error -5500 envNotPresent: returned by glue.
* error -5044 afpInsideTrashErr: the folder being shared is inside the trash folder OR the shared folder is being moved into the trash folder OR the folder is being moved to the trash and it contains a shared folder
* error -5043 afpInsideSharedErr: the folder being shared is inside a shared folder OR the folder contains a shared folder and is being moved into a shared folder OR the folder contains a shared folder and is being moved into the descendent of a shared folder.
* error -5042 afpPwdExpiredErr: the password being used is too old: this requires the user to change the password before log-in can continue
* error -5041 afpPwdTooShortErr: the password being set is too short: there is a minimum length that must be met or exceeded
* error -5040 afpPwdSameErr: someone tried to change their password to the same password on a mantadory password change
* error -5039 afpBadIDErr
* error -5038 afpSameObjectErr
* error -5037 afpCatalogChanged
* error -5036 afpDiffVolErr
* error -5035 afpIDExists
* error -5034 afpIDNotFound
* error -5033 afpContainsSharedErr: the folder being shared contains a shared folder
* error -5032 afpObjectLocked: Object is MRDW inhibited
* error -5031 afpVolLocked: Volume is Read-Only
* error -5030 afpIconTypeError
* error -5029 afpDirNotFound
* error -5028 afpCantRename
* error -5027 afpServerGoingDown
* error -5026 afpTooManyFilesOpen
* error -5025 afpObjectTypeErr
* error -5024 afpCallNotSupported
* error -5023 afpUserNotAuth
* error -5022 afpSessClosed
* error -5021 afpRangeOverlap
* error -5020 afpRangeNotLocked
* error -5019 afpParmErr
* error -5018 afpObjectNotFound
* error -5017 afpObjectExists
* error -5016 afpNoServer
* error -5015 afpNoMoreLocks
* error -5014 afpMiscErr
* error -5013 afpLockErr
* error -5012 afpItemNotFound
* error -5011 afpFlatVol
* error -5010 afpFileBusy
* error -5009 afpEofError
* error -5008 afpDiskFull
* error -5007 afpDirNotEmpty
* error -5006 afpDenyConflict
* error -5005 afpCantMove
* error -5004 afpBitmapErr
* error -5003 afpBadVersNum
* error -5002 afpBadUAM
* error -5001 afpAuthContinue
* error -5000 afpAccessDenied
* error -4009 noHelpForItem
* error -4008 badProfileError
* error -4007 colorSyncNotInstalled
* error -4006 pickerCantLive
* error -4005 cantLoadPackage
* error -4004 cantCreatePickerWindow
* error -4003 cantLoadPicker
* error -4002 pickerResourceError
* error -4001 requiredFlagsDontMatch
* error -4000 invalidPickerType
* error -3180 kOTCanceledErr: An outstanding call was canceled.
* error -3179 kOTBadSyncErr: A call to Sync was made at non-SystemTask time.
* error -3178 kOTProtocolErr: An unspecified protocol error occurred.
* error -3177 kOTQFullErr: The maximum number of outstanding indications has been reached for the endpoint.
* error -3176 kOTResAddressErr: The address to which this endpoint is bound differs from that of the endpoint that received the connection request; thus, this endpoint cannot accept this connection request.
* error -3175 kOTResQLenErr: When this endpoint was bound (see Bind), the qlen parameter was greater than zero. But to accept a connection on an alternate end-point, such as this one, the endpoint must be bound with a qlen parameter equal to zero.
* error -3174 kOTProviderMismatchErr: The endpoint that is to accept the connection is not the same kind of endpoint as this one.
* error -3173 kOTIndOutErr: There are outstanding connection indications on the endpoint. All other connection indications must be handled either by rejecting them with SndDisconnect, or by accepting them with Accept.
* error -3172 kOTAddressBusyErr: The requested address is in use, or this endpoint does not support multiple connections with the same local and remote addresses. This result code indicates that a connection already exists. As a return value for a Bind call, it may also indicate that no dynamic addresses are available for protocols or configuration methods that allow dynamic addressing.
* error -3171 kOTBadQLenErr: The argument qlen when the endpoint was bound with Bind was zero.
* error -3170 kOTBadNameErr: The endpoint name is invalid.
* error -3169 kOTStructureTypeErr: An unsupported structure type was passed in the structType field. This error is also returned when the structType field is inconsistent with the endpoint type.
* error -3168 kOTStateChangeErr: The endpoint is undergoing a transient state change. This error is returned when a function call is made while an endpoint is in the process of changing states.
* error -3167 kOTNotSupportedErr: This action is not supported by this endpoint.
* error -3166 kOTNoReleaseErr: No orderly release indication currently exists on this endpoint.
* error -3165 kOTBadFlagErr: An invalid flag was specified.
* error -3164 kOTNoUDErrErr: No unit data error indication currently exists on this endpoint.
* error -3163 kOTNoDisconnectErr: No disconnect indication is available.
* error -3162 kOTNoDataErr: This endpoint is in non-blocking mode, but no data is currently available. It is also returned by LookupName when no names are found.
* error -3161 kOTFlowErr: The endpoint is in asynchronous mode, but the flow control mechanism prevents the endpoint from accepting any data at this time.
* error -3160 kOTBufferOverflowErr: The number of bytes allocated to hold a result is greater than zero, but not sufficient to store the result.
* error -3159 kOTBadDataErr: The amount of client data specified was not within the bounds allowed by the endpoint.
* error -3158 kOTLookErr: An asynchronous event has occurred on this endpoint.
* error -3156 kOTBadSequenceErr: An invalid sequence number was specified, or a NULL call pointer was specified when rejecting a connection request.
* error -3155 kOTOutStateErr: The function was issued in the wrong sequence.
* error -3154 kOTNoAddressErr: The endpoint could not allocate an address, or an address was required and not supplied by the client.
* error -3153 kOTBadReferenceErr: The specified EndpointRef or TEndpoint* does not refer to a valid endpoint.
* error -3152 kOTAccessErr: The user does not have permission to negotiate the specified address or options.
* error -3151 kOTBadOptionErr: The specified protocol options were in an incorrect format or contained illegal information.
* error -3150 kOTBadAddressErr: The specified protocol address was in an incorrect format or contained illegal information.
* error -3109 sktClosedErr
* error -3108 recNotFnd
* error -3107 atpBadRsp
* error -3106 atpLenErr
* error -3105 readQErr
* error -3104 extractErr
* error -3103 ckSumErr
* error -3102 noMPPErr
* error -3101 buf2SmallErr
* error -3032 noPrefAppErr
* error -3031 badTranslationSpecErr
* error -3030 noTranslationPathErr
* error -3026 couldNotParseSourceFileErr: Source document does not contain source type
* error -3025 invalidTranslationPathErr: Source type to destination type not a valid path
* error -3003 componentDontRegister
* error -3002 componentNotCaptured
* error -3001 validInstancesExist
* error -3000 invalidComponentID
* error -2899 fragLastErrCode: ie: an application's main fragment had no entry point - or - an accerated resource had no entry point or it had a termination routine etc...
* error -2824 fragInvalidFragmentUsage: fragment targeted for an unacceptable architecture
* error -2823 fragArchError: no application found in cfrg (for Process Manager)
* error -2822 fragAppNotFound: user intialization routine did not return noErr
* error -2821 fragUserInitProcErr: fragment container corrupted (known format)
* error -2820 fragCorruptErr: internal inconstistancy
* error -2819 fragConstErr: error in initailization of this manager
* error -2818 fragMgrInitErr: error connecting to library (error occured in sub prepare)
* error -2817 fragLibConnErr: boot library has initialization routine
* error -2816 fragInitRtnUsageErr: circularity detected in mandatory initialization order
* error -2815 fragInitLoop: import library was too new and therefore incompatible
* error -2814 fragImportTooNew: import library was too old and therefore incompatible
* error -2813 fragImportTooOld: order error during user initialization function invocation
* error -2812 fragObjectInitSeqErr: no more context idÕs
* error -2811 fragNoContextIDs: out of memory in user's address space for loadable section
* error -2810 fragNoAddrSpace: out of memory for interal bookkeeping
* error -2809 fragNoMem: unused
* error -2808 fragUnused1: loaded fragment had "hard" unresolved imports
* error -2807 fragHadUnresolveds: fragment container format unknown
* error -2806 fragFormatUnknown: registered name already in use
* error -2805 fragDupRegLibName: library name not found in Frag registry
* error -2804 fragLibNotFound: section was not found
* error -2803 fragSectionNotFound: symbol was not found in connection
* error -2802 fragSymbolNotFound: connecionID was not valid
* error -2801 fragConnectionIDNotFound: contextID was not valid
* error -2800 fragContextNotFound: CFM error codes
* error -2780 errASInconsistentNames
* error -2763 errASNoResultReturned
* error -2762 errASParameterNotForEvent
* error -2761 errASIllegalFormalParameter
* error -2760 errASTerminologyNestingTooDeep
* error -2721 errASCantCompareMoreThan32k
* error -2720 errASCantConsiderAndIgnore
* error -2526 mmInternalError: drag was not accepted by receiver
* error -2519 tsmUnknownErr: unSupported interface type error
* error -2518 tsmUnsupportedTypeErr: script has no imput method or is using old IM
* error -2517 tsmScriptHasNoIMErr: returned by GetDefaultInputMethod
* error -2516 tsmInputMethodIsOldErr: text service already opened for the document
* error -2515 tsmComponentAlreadyOpenErr: text service is not open
* error -2514 tsmTSNotOpenErr: the text service has no menu
* error -2513 tsmTSHasNoMenuErr: not TSM aware because we are using input window
* error -2512 tsmUseInputWindowErr: there are open documents
* error -2511 tsmDocumentOpenErr: no text service found
* error -2510 tsmTextServiceNotFoundErr: canÕt open the component
* error -2509 tsmCantOpenComponentErr: no open text service
* error -2508 tsmNoOpenTSErr: document is NOT active
* error -2507 tsmDocNotActiveErr: document is still active
* error -2506 tsmTSMDocBusyErr: invalid TSM documentation id
* error -2505 tsmInvalidDocIDErr: app never registered error (not TSM aware)
* error -2504 tsmNeverRegisteredErr: want to register again error
* error -2503 tsmAlreadyRegisteredErr: not an application error
* error -2502 tsmNotAnAppErr: component result no error
* error -2501 tsmInputMethodNotFoundErr
* error -2500 tsmUnsupScriptLanguageErr
* error -2209 badCallOrderErr: Usually due to a status call being called prior to being setup first
* error -2208 noDMAErr: CanÕt do DMA digitizing (i.e. can't go to requested dest
* error -2207 badDepthErr: CanÕt digitize into this depth
* error -2206 notExactSizeErr: CanÕt do exact size requested
* error -2205 noMoreKeyColorsErr: all key indexes in use
* error -2204 notExactMatrixErr: warning of bad matrix digitizer did its best
* error -2203 matrixErr: bad matrix digitizer did nothing
* error -2202 qtParamErr: bad input parameter (out of range etc)
* error -2201 digiUnimpErr: feature unimplemented
* error -2062 movieTextNotFoundErr
* error -2059 samplesAlreadyInMediaErr
* error -2058 auxiliaryExportDataUnavailable
* error -2057 unsupportedAuxiliaryImportData
* error -2056 soundSupportNotAvailableErr: QT for Windows error
* error -2055 noSoundTrackInMovieErr: QT for Windows error
* error -2054 noVideoTrackInMovieErr: QT for Windows error
* error -2053 featureUnsupported
* error -2052 couldNotUseAnExistingSample
* error -2051 noDefaultDataRef
* error -2050 badDataRefIndex
* error -2049 invalidDataRefContainer
* error -2048 noMovieFound
* error -2047 dataNoDataRef
* error -2046 endOfDataReached
* error -2045 dataAlreadyClosed
* error -2044 dataAlreadyOpenForWrite
* error -2043 dataNotOpenForWrite
* error -2042 dataNotOpenForRead
* error -2041 invalidSampleDescription
* error -2040 invalidChunkCache
* error -2039 invalidSampleDescIndex
* error -2038 invalidChunkNum
* error -2037 invalidSampleNum
* error -2036 invalidRect
* error -2035 cantEnableTrack
* error -2034 internalQuickTimeError
* error -2033 badEditIndex
* error -2032 timeNotInMedia
* error -2031 timeNotInTrack
* error -2030 trackNotInMovie
* error -2029 trackIDNotFound
* error -2028 badTrackIndex
* error -2027 maxSizeToGrowTooSmall
* error -2026 userDataItemNotFound
* error -2025 staleEditState
* error -2024 nonMatchingEditState
* error -2023 invalidEditState
* error -2022 cantCreateSingleForkFile: happens when file already exists
* error -2021 wfFileNotFound
* error -2020 movieToolboxUninitialized
* error -2019 progressProcAborted
* error -2018 mediaTypesDontMatch
* error -2017 badEditList
* error -2016 cantPutPublicMovieAtom
* error -2015 invalidTime
* error -2014 invalidDuration
* error -2013 invalidHandler
* error -2012 invalidDataRef
* error -2011 invalidSampleTable
* error -2010 invalidMovie
* error -2009 invalidTrack
* error -2008 invalidMedia
* error -2007 noDataHandler
* error -2006 noMediaHandler
* error -2005 badComponentType
* error -2004 cantOpenHandler
* error -2003 cantFindHandler
* error -2002 badPublicMovieAtom
* error -2001 badImageDescription
* error -2000 couldNotResolveDataRef
* error -1857 dragNotAcceptedErr: handler not found
* error -1856 handlerNotFoundErr: handler already exists
* error -1855 duplicateHandlerErr: error while trying to get flavor data
* error -1854 cantGetFlavorErr: flavor type already exists
* error -1853 duplicateFlavorErr: unknown flavor type
* error -1852 badDragFlavorErr: unknown drag item reference
* error -1851 badDragItemErr: unknown drag reference
* error -1850 badDragRefErr: Drag Manager error codes
* error -1813 errEndOfBody
* error -1812 errEndOfDocument
* error -1811 errTopOfBody
* error -1810 errTopOfDocument
* error -1801 errOffsetIsOutsideOfView
* error -1800 errOffsetInvalid
* error -1762 errOSACantOpenComponent: Can't connect to scripting system with that ID
* error -1761 errOSAComponentMismatch: Parameters are from 2 different components
* error -1759 errOSADataFormatTooNew
* error -1758 errOSADataFormatObsolete
* error -1757 errOSANoSuchDialect
* error -1756 errOSASourceNotAvailable
* error -1754 errOSABadSelector
* error -1753 errOSAScriptError
* error -1752 errOSABadStorageType
* error -1751 errOSAInvalidID
* error -1750 errOSASystemError
* error -1732 errAERecordingIsAlreadyOn: available only in version 1.0.1 or greater
* error -1731 errAEUnknownObjectType: available only in version 1.0.1 or greater
* error -1730 errAEEmptyListContainer: Attempt to pass empty list as container to accessor
* error -1729 errAENegativeCount: CountProc returned negative value
* error -1728 errAENoSuchObject: e.g.: specifier asked for the 3rd but there are only 2. Basically this indicates a run-time resolution error.
* error -1727 errAENotAnObjSpec: Param to AEResolve not of type 'obj '
* error -1726 errAEBadTestKey: Test is neither typeLogicalDescriptor nor typeCompDescriptor
* error -1725 errAENoSuchLogical: Something other than AND OR or NOT
* error -1723 errAEAccessorNotFound: Accessor proc matching wantClass and containerType or wildcards not found
* error -1721 errAEWrongNumberArgs: Logical op kAENOT used with other than 1 term
* error -1720 errAEImpossibleRange: A range like 3rd to 2nd or 1st to all.
* error -1719 errAEIllegalIndex: index is out of range in a put operation
* error -1718 errAEReplyNotArrived: the contents of the reply you are accessing have not arrived yet
* error -1717 errAEHandlerNotFound: no handler in the dispatch tables fits the parameters to AEGetEventHandler or AEGetCoercionHandler
* error -1716 errAEUnknownAddressType: the target address type is not known
* error -1715 errAEParamMissed: a required parameter was not accessed
* error -1714 errAENotASpecialFunction: there is no special function forwith this keyword
* error -1713 errAENoUserInteraction: no user interaction is allowed
* error -1712 errAETimeout: the AppleEvent timed out
* error -1711 errAEWaitCanceled: in AESend the user cancelled out of wait loop for reply or receipt
* error -1710 errAEUnknownSendMode: mode wasn't NoReply WaitReply or QueueReply or Interaction level is unknown
* error -1709 errAEReplyNotValid: AEResetTimer was passed an invalid reply parameter
* error -1708 errAEEventNotHandled: the AppleEvent was not handled by any handler
* error -1707 errAENotAppleEvent: the event is not in AppleEvent format
* error -1706 errAENewerVersion: need newer version of the AppleEvent manager
* error -1705 errAEBadListItem: the specified list item does not exist
* error -1704 errAENotAEDesc
* error -1703 errAEWrongDataType
* error -1702 errAECorruptData
* error -1701 errAEDescNotFound
* error -1700 errAECoercionFail: bad parameter data or unable to coerce the data supplied
* error -1310 fsDataTooBigErr: file or volume is too big for system
* error -1309 fileBoundsErr: file's EOF offset mark or size is too big
* error -1308 notARemountErr: when _Mount allows only remounts and doesn't get one
* error -1307 badFidErr: file id is dangling or doesn't match with the file number
* error -1306 sameFileErr: can't exchange a file with itself
* error -1305 desktopDamagedErr: desktop database files are corrupted
* error -1304 catChangedErr: the catalog has been modified
* error -1303 diffVolErr: files on different volumes
* error -1302 notAFileErr: directory specified
* error -1301 fidExists: file id already exists
* error -1300 fidNotFound: no file thread exists.
* error -1280 errRefNum: bad connection refNum
* error -1279 errAborted: control call was aborted
* error -1278 errState: bad connection state for this operation
* error -1277 errOpening: open connection request failed
* error -1276 errAttention: attention message too long
* error -1275 errFwdReset: read terminated by forward reset
* error -1274 errDSPQueueSize: DSP ReadWrite Queue Too small
* error -1273 errOpenDenied: open connection request was denied
* error -1105 reqAborted
* error -1104 noDataArea
* error -1103 noSendResp
* error -1102 cbNotFound
* error -1101 noRelErr
* error -1100 badBuffNum
* error -1099 badATPSkt
* error -1098 tooManySkts
* error -1097 tooManyReqs
* error -1096 reqFailed
* error -1075 aspNoAck: No ack on attention request (server err)
* error -1074 aspTooMany: Too many clients (server error)
* error -1073 aspSizeErr: Command block too big
* error -1072 aspSessClosed: Session closed
* error -1071 aspServerBusy: Server cannot open another session
* error -1070 aspParamErr: Parameter error
* error -1069 aspNoServers: No servers at that address
* error -1068 aspNoMoreSess: No more sessions on server
* error -1067 aspBufTooSmall: Buffer too small
* error -1066 aspBadVersNum: Server cannot support this ASP version
* error -1029 nbpNISErr: Error trying to open the NIS
* error -1028 nbpNotFound: Name not found on remove
* error -1027 nbpDuplicate: Duplicate name exists already
* error -1026 nbpConfDiff: Name confirmed at different socket
* error -1025 nbpNoConfirm
* error -1024 nbpBuffOvr: Buffer overflow in LookupName
* error -1000 noMaskFoundErr: Icon Utilties Error
* error -932 guestNotAllowedErr: destination port requires authentication
* error -931 badLocNameErr: location name malformed
* error -930 badServiceMethodErr: illegal service type or not supported
* error -928 noUserRecErr: Invalid user reference number
* error -927 authFailErr: unable to authenticate user at destination
* error -926 noInformErr: PPCStart failed because destination did not have inform pending
* error -925 networkErr: An error has occured in the network not too likely
* error -924 noUserRefErr: unable to create a new userRefNum
* error -923 notLoggedInErr: The default userRefNum does not yet exist
* error -922 noDefaultUserErr: user hasn't typed in owners name in Network Setup Control Pannel
* error -919 badPortNameErr: PPCPortRec malformed
* error -917 sessClosedErr: session was closed
* error -916 portClosedErr: port was closed
* error -915 noResponseErr: unable to contact destination
* error -914 noToolboxNameErr: A system resource is missing not too likely
* error -913 noMachineNameErr: user hasn't named his Macintosh in the Network Setup Control Panel
* error -912 userRejectErr: Destination rejected the session request
* error -911 noUserNameErr: user name unknown on destination machine
* error -910 portNameExistsErr: port is already open (perhaps in another app)
* error -909 badReqErr: bad parameter or invalid state for operation
* error -908 noSessionErr: Invalid session reference number
* error -907 sessTableErr: Out of session tables try again later
* error -906 destPortErr: Port does not exist at destination
* error -905 localOnlyErr: Network activity is currently disabled
* error -904 noGlobalsErr: The system is hosed better re-boot
* error -903 noPortErr: Unable to open port or bad portRefNum
* error -902 nameTypeErr: Invalid or inappropriate locationKindSelector in locationName
* error -900 notInitErr: PPCToolBox not initialized
* error -863 hmCloseViewActive: Returned from HMRemoveBalloon if CloseView was active
* error -862 hmNoBalloonUp: Returned from HMRemoveBalloon if no balloon was visible when call was made
* error -861 hmOperationUnsupported: Returned from HMShowBalloon call if bad method passed to routine
* error -859 hmUnknownHelpType: Returned if help msg record contained a bad type
* error -858 hmWrongVersion: Returned if help mgr resource was the wrong version
* error -857 hmSkippedBalloon: Returned from calls if helpmsg specified a skip balloon
* error -855 hmHelpManagerNotInited: Returned from HMGetHelpMenuHandle if help menu not setup
* error -854 hmSameAsLastBalloon: Returned from HMShowMenuBalloon if menu & item is same as last time
* error -853 hmBalloonAborted: Returned if mouse was moving or mouse wasn't in window port rect
* error -850 hmHelpDisabled: Show Balloons mode was off call to routine ignored
* error -813 rcDBPackNotInited: incompatible versions
* error -812 rcDBWrongVersion: no app handler for specified data type
* error -811 rcDBNoHandler: tried to kill a bad pb
* error -810 rcDBBadAsyncPB: ddev does not support async calls
* error -809 rcDBAsyncNotSupp: bad ddev specified on DBInit
* error -808 rcDBBadDDEV: bad session number for DBGetConnInfo
* error -807 rcDBBadSessNum: Database access error codes
* error -806 rcDBBadSessID
* error -805 rcDBExec
* error -804 rcDBBreak
* error -803 rcDBBadType
* error -802 rcDBError
* error -801 rcDBValue
* error -800 rcDBNull
* error -626 noMMUErr: no MMU present
* error -625 cannotDeferErr: unable to defer additional functions
* error -624 interruptsMaskedErr: donÕt call with interrupts masked
* error -623 notLockedErr: specified range of memory is not locked
* error -622 cannotMakeContiguousErr: cannot make specified range contiguous
* error -621 notHeldErr: specified range of memory is not held
* error -620 notEnoughMemoryErr: insufficient physical memory
* error -619 threadProtocolErr
* error -618 threadNotFoundErr
* error -617 threadTooManyReqsErr
* error -610 noUserInteractionAllowed: no user interaction allowed
* error -609 connectionInvalid
* error -608 noOutstandingHLE
* error -607 bufferIsSmall: error returns from Post and Accept
* error -606 appIsDaemon: app is BG-only and launch flags disallow this
* error -605 appMemFullErr: application SIZE not big enough for launch
* error -604 hardwareConfigErr: hardware configuration not correct for call
* error -603 protocolErr: app made module calls in improper order
* error -602 appModeErr: memory mode is 32-bit but app not 32-bit clean
* error -601 memFragErr: not enough room to launch app wspecial requirements
* error -600 procNotFound: no eligible process with specified descriptor
* error -502 hwParamErr: bad selector for _HWPriv
* error -501 teScrapSizeErr: scrap item too big for text edit record
* error -500 rgnTooBigErr
* error -492 exUserBreak: user debugger break; execute debugger commands on stack
* error -491 strUserBreak: user debugger break; display string on stack
* error -490 userBreak: user debugger break
* error -463 notThePublisherWrn: not the first registered publisher for that container
* error -462 containerAlreadyOpenWrn: container already opened by this section
* error -461 containerNotFoundWrn: could not find editionContainer at this time
* error -460 multiplePublisherWrn: A Publisher is already registered for that container
* error -454 badSubPartErr: can not use sub parts in this release
* error -453 badEditionFileErr: edition file is corrupt
* error -452 notRegisteredSectionErr: not a registered SectionRecord
* error -451 badSectionErr: not a valid SectionRecord
* error -450 editionMgrInitErr: edition manager not inited by this app
* error -417 btKeyAttrErr: There is no such a key attribute.
* error -416 btKeyLenErr: Maximum key length is too long or equal to zero.
* error -415 btRecNotFnd: Record cannot be found.
* error -414 btDupRecErr: Record already exists.
* error -413 btNoSpace: Can't allocate disk space.
* error -410 notBTree: The file is not a dictionary.
* error -400 gcrOnMFMErr: gcr format on high density media error
* error -360 slotNumErr: invalid slot # error
* error -351 smRecNotFnd: Record not found in the SRT.
* error -350 smSRTOvrFlErr: SRT over flow.
* error -349 smNoGoodOpens: No opens were successfull in the loop.
* error -348 smOffsetErr: Offset was too big (temporary error
* error -347 smByteLanesErr: NumByteLanes was determined to be zero.
* error -346 smBadsPtrErr: Bad pointer was passed to sCalcsPointer
* error -345 smsGetDrvrErr: Error occurred during _sGetDriver.
* error -344 smNoMoresRsrcs: No more sResources
* error -343 smDisDrvrNamErr: Error occured during _sDisDrvrName.
* error -342 smGetDrvrNamErr: Error occured during _sGetDrvrName.
* error -341 smCkStatusErr: Status of slot fail.
* error -340 smBlkMoveErr: _BlockMove error
* error -339 smNewPErr: _NewPtr error
* error -338 smSelOOBErr: Selector out of bounds error
* error -337 smSlotOOBErr: Slot out of bounds error
* error -336 smNilsBlockErr: Nil sBlock error (Dont allocate and try to use a nil sBlock)
* error -335 smsPointerNil: LPointer is nil From sOffsetData. If this error occurs; check sInfo rec for more information.
* error -334 smCPUErr: Code revision is wrong
* error -333 smCodeRevErr: Code revision is wrong
* error -332 smReservedErr: Reserved field not zero
* error -331 smBadsList: Bad sList: Id1 < Id2 < Id3 ...format is not followed.
* error -330 smBadRefId: Reference Id not found in List
* error -320 smBusErrTO: BusError time out.
* error -319 smBadBoardId: BoardId was wrong; re-init the PRAM record.
* error -318 smNoJmpTbl: SDM jump table could not be created. or smReservedSlot: slot is reserved VM should not use this address space.
* error -317 smInitTblVErr: An error occured while trying to initialize the Slot Resource Table.
* error -316 smInitStatVErr: The InitStatusV field was negative after primary or secondary init.
* error -315 smNoBoardId: No Board Id.
* error -314 smGetPRErr: Error occured during _sGetPRAMRec (See SIMStatus).
* error -313 smNoBoardSRsrc: No Board sResource.
* error -312 smDisposePErr: _DisposePointer error
* error -311 smFHBlkDispErr: Error occured during _sDisposePtr (Dispose of FHeader block).
* error -310 smFHBlockRdErr: Error occured during _sGetFHeader.
* error -309 smBLFieldBad: ByteLanes field was bad.
* error -308 smUnExBusErr: Unexpected BusError
* error -307 smResrvErr: Fatal reserved error. Resreved field <> 0.
* error -306 smNosInfoArray: No sInfoArray. Memory Mgr error.
* error -305 smDisabledSlot: This slot is disabled (-305 use to be smLWTstBad)
* error -304 smNoDir: Directory offset is Nil
* error -303 smRevisionErr: Wrong revison level
* error -302 smFormatErr: FHeader Format is not Apple's
* error -301 smCRCFail: CRC check failed for declaration data
* error -300 smEmptySlot: No card in slot
* error -299 nmTypErr: wrong queue type
* error -293 smPriInitErr: Error; Cards could not be initialized.
* error -292 smPRAMInitErr: Error; Slot Resource Table could not be initialized.
* error -291 smSRTInitErr: Error; Slot Resource Table could not be initialized.
* error -290 smSDMInitErr: Error; SDM could not be initialized.
* error -261 midiInvalidCmdErr: command not supported for port type
* error -260 midiDupIDErr: duplicate client ID
* error -259 midiNameLenErr: name supplied is longer than 31 characters
* error -258 midiWriteErr: MIDIWritePacket couldn't write to all connected ports
* error -257 midiNoConErr: no connection exists between specified ports
* error -256 midiVConnectRmvd: pending virtual connection removed
* error -255 midiVConnectMade: pending virtual connection resolved
* error -254 midiVConnectErr: pending virtual connection created
* error -253 midiTooManyConsErr: too many connections made
* error -252 midiTooManyPortsErr: too many ports already installed in the system
* error -251 midiNoPortErr: no port with that ID found
* error -250 midiNoClientErr: no client with that ID found
* error -247 badInputText
* error -246 badDictFormat
* error -245 incompatibleVoice
* error -244 voiceNotFound
* error -243 bufTooSmall
* error -242 synthNotReady
* error -241 synthOpenFailed
* error -240 noSynthFound
* error -232 siUnknownQuality: invalid quality selector (returned by driver)
* error -231 siUnknownInfoType: invalid info type selector (returned by driver)
* error -230 siInputDeviceErr: input device hardware failure
* error -229 siBadRefNum: invalid input device reference number
* error -228 siBadDeviceName: input device could not be opened
* error -227 siDeviceBusyErr: input device already in use
* error -226 siInvalidSampleSize: invalid sample size
* error -225 siInvalidSampleRate: invalid sample rate
* error -224 siHardDriveTooSlow: hard drive too slow to record to disk
* error -223 siInvalidCompression: invalid compression type
* error -222 siNoBufferSpecified: returned by synchronous SPBRecord if nil buffer passed
* error -221 siBadSoundInDevice: invalid index passed to SoundInGetIndexedDevice
* error -220 siNoSoundInHardware: no Sound Input hardware
* error -212 noMoreRealTime: not enough CPU cycles left to add another task
* error -211 channelNotBusy
* error -210 buffersTooSmall: can not operate in the memory allowed
* error -209 channelBusy: the Channel is being used for a PFD already
* error -208 badFileFormat: was not type AIFF or was of bad formatcorrupt
* error -207 notEnoughBufferSpace: could not allocate enough memory
* error -206 badFormat: Sound Manager Error Returns
* error -205 badChannel: Sound Manager Error Returns
* error -204 resProblem: Sound Manager Error Returns
* error -203 queueFull: Sound Manager Error Returns
* error -201 notEnoughHardwareErr: Sound Manager Error Returns
* error -200 noHardwareErr: Sound Manager Error Returns
* error -199 mapReadErr: map inconsistent with operation
* error -198 resAttrErr: attribute inconsistent with operation
* error -197 rmvRefFailed: RmveReference failed
* error -196 rmvResFailed: RmveResource failed
* error -195 addRefFailed: AddReference failed
* error -194 addResFailed: AddResource failed
* error -193 resFNotFound: Resource file not found
* error -192 resNotFound: Resource not found
* error -190 inputOutOfBounds: Offset of Count out of bounds
* error -189 writingPastEnd: Writing past end of file
* error -188 resourceInMemory: Resource already in memory
* error -186 CantDecompress: resource bent ("the bends") - can't decompress a compressed resource
* error -185 badExtResource: extended resource has a bad format.
* error -157 cDepthErr: invalid pixel depth
* error -156 cResErr: invalid resolution for MakeITable
* error -155 cDevErr: invalid type of graphics device
* error -154 cProtectErr: colorTable entry protection violation
* error -153 cRangeErr: range error on colorTable request
* error -152 cNoMemErr: failed to allocate memory for structure
* error -151 cTempMemErr: failed to allocate memory for temporary structures
* error -150 cMatchErr: Color2Index failed to find an index
* error -149 insufficientStackErr or nsStackErr
* error -148 pixMapTooDeepErr
* error -147 rgnOverflowErr or rgnTooBigError
* error -145 noMemForPictPlaybackErr
* error -128 userCanceledErr
* error -127 hMenuFindErr: could not find HMenu's parent in MenuKey
* error -126 mBarNFnd: system error code for MBDF not found
* error -125 updPixMemErr: insufficient memory to update a pixmap
* error -124 volGoneErr: Server volume has been disconnected.
* error -123 wrgVolTypErr: Wrong volume type error [operation not supported for MFS]
* error -122 badMovErr: Move into offspring error
* error -121 tmwdoErr: No free WDCB available
* error -120 dirNFErr: Directory not found
* error -117 memLockedErr: trying to move a locked block (MoveHHi)
* error -116 memSCErr: Size Check failed
* error -115 memBCErr: Block Check failed
* error -114 memPCErr: Pointer Check failed
* error -113 memAZErr: Address in zone check failed
* error -112 memPurErr: trying to purge a locked or non-purgeable block
* error -111 memWZErr: WhichZone failed (applied to free block)
* error -110 memAdrErr: address was odd; or out of range
* error -109 nilHandleErr: Master Pointer was NIL in HandleZone or other
* error -108 iMemFullErr or memFullErr: Not enough room in heap zone
* error -102 noTypeErr: No object of that type in scrap
* error -100 noScrapErr: No scrap exists error
* error -99 memROZWarn: soft error in ROZ or memROZError: hard error in ROZ or memROZErr: hard error in ROZ
* error -98 portNotCf: driver Open error code (parameter RAM not configured for this connection)
* error -97 portInUse: driver Open error code (port is in use)
* error -96 portNotPwr: serial port not currently powered
* error -95 excessCollsns: excessive collisions on write
* error -94 lapProtErr: error in attachingdetaching protocol
* error -93 noBridgeErr: no network bridge for non-local send
* error -92 ddpLenErr: data length too big or eLenErr: ENET error codes
* error -91 ddpSktErr: error in soket number or eMultiErr: Length error ddpLenErr
* error -90 breakRecd: Break received (SCC)
* error -89 rcvrErr: SCC receiver error (framing; parity; OR)
* error -88 prInitErr: InitUtil found the parameter ram uninitialized
* error -87 prWrErr: parameter ram written didn't read-verify
* error -86 clkWrErr: time written did not verify
* error -85 clkRdErr: unable to read same clock value twice
* error -84 firstDskErr: IO System Errors or verErr: track failed to verify
* error -83 fmt2Err: can't get enough sync
* error -82 fmt1Err: can't find sector 0 after track format
* error -81 sectNFErr: sector number never found on a track
* error -80 seekErr: track number wrong on address mark
* error -79 spdAdjErr: unable to correctly adjust disk speed
* error -78 twoSideErr: tried to read 2nd side on a 1-sided drive
* error -77 initIWMErr: unable to initialize IWM
* error -76 tk0BadErr: track 0 detect doesn't change
* error -75 cantStepErr: step handshake failed
* error -74 wrUnderrun: write underrun occurred
* error -73 badDBtSlp: bad data mark bit slip nibbles
* error -72 badDCksum: bad data mark checksum
* error -71 noDtaMkErr: couldn't find a data mark header
* error -70 badBtSlpErr: bad addr mark bit slip nibbles
* error -69 badCksmErr: addr mark checksum didn't check
* error -68 dataVerErr: read verify compare failed
* error -67 noAdrMkErr: couldn't find valid addr mark
* error -66 fontSubErr: font substitution occured or noNybErr: couldn't find 5 nybbles in 200 tries
* error -65 fontNotDeclared: font not declared or offLinErr: rw requested for an off-line drive
* error -64 fontDecError: error during font declaration or lastDskErr: IO System Errors or noDriveErr: drive not installed
* error -61 wrPermErr: write permissions error
* error -60 badMDBErr: bad master directory block
* error -59 fsRnErr: file system internal error:during rename the old entry was deleted but could not be restored.
* error -58 extFSErr: volume in question belongs to an external fs
* error -57 noMacDskErr: not a mac diskette (sig bytes are wrong)
* error -56 nsDrvErr: no such drive (tried to mount a bad drive num)
* error -55 volOnLinErr: drive volume already on-line at MountVol
* error -54 permErr: permissions error (on file open)
* error -53 volOffLinErr: volume not on line error (was Ejected)
* error -52 gfpErr: get file position error
* error -51 rfNumErr: refnum error
* error -50 paramErr: error in user parameter list
* error -49 opWrErr: file already open with with write permission
* error -48 dupFNErr: duplicate filename (rename)
* error -47 fBsyErr: File is busy (delete)
* error -46 vLckdErr: volume is locked
* error -45 fLckdErr: file is locked
* error -44 wPrErr: diskette is write protected.
* error -43 fnfErr: File not found
* error -42 tmfoErr: too many files open
* error -41 mFulErr: memory full (open) or file won't fit (load)
* error -40 posErr: tried to position to before start of file (rw)
* error -39 eofErr: End of file
* error -38 fnOpnErr: File not open
* error -37 bdNamErr: there may be no bad names in the final system!
* error -36 ioErr: IO error (bummers)
* error -35 nsvErr: no such volume
* error -34 dskFulErr: disk full
* error -33 dirFulErr: Directory full
* error -30 dceExtErr: dce extension error
* error -29 unitTblFullErr: unit table has no more entries
* error -28 notOpenErr: Couldn't rdwrctlsts cause driver not opened
* error -27 abortErr: IO call aborted by KillIO or iIOAbortErr: IO abort error (Printing Manager) or iIOAbort
* error -26 dInstErr: DrvrInstall couldn't find driver in resources
* error -25 dRemovErr: tried to remove an open driver
* error -24 closErr: IO System Errors
* error -23 openErr: IO System Errors
* error -22 unitEmptyErr: IO System Errors
* error -21 badUnitErr: IO System Errors
* error -20 writErr: IO System Errors
* error -19 readErr: IO System Errors
* error -18 statusErr: IO System Errors
* error -17 controlErr: IO System Errors
* error -13 dsExtensionsDisabled: say ÒExtensions DisabledÓ
* error -12 dsHD20Installed: say ÒHD20 StartupÓ
* error -11 dsDisassemblerInstalled: say ÒDisassembler InstalledÓ
* error -10 dsMacsBugInstalled: say ÒMacsBug InstalledÓ
* error -8 seNoDB: no debugger installed to handle debugger command
* error -5 SlpTypeErr: invalid queue element
* error -4 unimpErr: unimplemented core routine
* error -3 corErr: core routine number out of range
* error -2 vTypErr: invalid queue element
* error -1 qErr: queue element not found during deletion or telGenericError
* error errAECorruptData errOSACorruptData
* error dsCDEFNotFound CDEFNFnd
* error dsWDEFNotFound WDEFNFnd
* error noHardwareErr noHardware: obsolete spelling
* error errAERecordingIsAlreadyOn errOSARecordingIsAlreadyOn
* error notEnoughHardwareErr notEnoughHardware: obsolete spelling
* error movieToolboxUninitialized noRecordOfApp: replica
* error 1 evtNotEnb: event not enabled at PostEvent or siInitSDTblErr: slot int dispatch table could not be initialized. or dsBusError: bus error
* error 2 siInitVBLQsErr: VBLqueues for all slots could not be initialized. or dsAddressErr: address error
* error 3 siInitSPTblErr: slot priority table could not be initialized. or dsIllInstErr: illegal instruction error
* error 4 dsZeroDivErr: zero divide error
* error 5 dsChkErr: check trap error
* error 6 dsOvflowErr: overflow trap error
* error 7 dsPrivErr: privilege violation error
* error 8 telNoTools: no telephone tools found in extension folder or dsTraceErr: trace mode error
* error 9 dsLineAErr: line 1010 trap error
* error 10 sdmJTInitErr: SDM Jump Table could not be initialized. or dsLineFErr: line 1111 trap error
* error 11 sdmInitErr: SDM could not be initialized. or dsMiscErr: miscellaneous hardware exception error
* error 12 sdmSRTInitErr: Slot Resource Table could not be initialized. or dsCoreErr: unimplemented core routine error
* error 13 sdmPRAMInitErr: Slot PRAM could not be initialized. or dsIrqErr: uninstalled interrupt error
* error 14 sdmPriInitErr: Cards could not be initialized. or dsIOCoreErr: IO Core Error
* error 15 dsLoadErr: Segment Loader Error
* error 16 dsFPErr: Floating point error
* error 17 dsNoPackErr: package 0 not present
* error 18 dsNoPk1: package 1 not present
* error 19 dsNoPk2: package 2 not present
* error 20 dsNoPk3: package 3 not present
* error 21 dsNoPk4: package 4 not present
* error 22 dsNoPk5: package 5 not present
* error 23 dsNoPk6: package 6 not present
* error 24 dsNoPk7: package 7 not present
* error 25 dsMemFullErr: out of memory!
* error 26 dsBadLaunch: can't launch file
* error 27 dsFSErr: file system map has been trashed
* error 28 dsStknHeap: stack has moved into application heap
* error 30 dsReinsert: request user to reinsert off-line volume
* error 31 dsNotThe1: not the disk I wanted
* error 33 negZcbFreeErr: ZcbFree has gone negative
* error 40 dsGreeting: welcome to Macintosh greeting
* error 41 dsFinderErr: can't load the Finder error
* error 42 shutDownAlert: handled like a shutdown error or dsBadStartupDisk: unable to mount boot volume (sad Mac only)
* error 43 dsSystemFileErr: canÕt find System file to open (sad Mac only)
* error 51 dsBadSlotInt: unserviceable slot interrupt
* error 81 dsBadSANEOpcode: bad opcode given to SANE Pack4
* error 83 dsBadPatchHeader: SetTrapAddress saw the Òcome-fromÓ header
* error 84 menuPrgErr: happens when a menu is purged
* error 85 dsMBarNFnd: Menu Manager Errors
* error 86 dsHMenuFindErr: Menu Manager Errors
* error 87 dsWDEFNotFound: could not load WDEF
* error 88 dsCDEFNotFound: could not load CDEF
* error 89 dsMDEFNotFound: could not load MDEF
* error 90 dsNoFPU: an FPU instruction was executed and the machine doesnÕt have one
* error 98 dsNoPatch: Can't patch for particular Model Mac
* error 99 dsBadPatch: Can't load patch resource
* error 101 dsParityErr: memory parity error
* error 102 dsOldSystem: System is too old for this ROM
* error 103 ds32BitMode: booting in 32-bit on a 24-bit sys
* error 104 dsNeedToWriteBootBlocks: need to write new boot blocks
* error 105 dsNotEnoughRAMToBoot: must have at least 1.5MB of RAM to boot 7.0
* error 106 dsBufPtrTooLow: bufPtr moved too far during boot
* error 1010 dsBadLibrary: DS Errors which are specific to the new runtime model introduced with PowerPC
* error 1011 dsMixedModeFailure: Bad shared library
* error 20000 dsShutDownOrRestart: user choice between ShutDown and Restart
* error 20001 dsSwitchOffOrRestart: user choice between switching off and Restart
* error 20002 dsForcedQuit: allow the user to ExitToShell return if Cancel
* error 20003 dsRemoveDisk: request user to remove disk from manual eject drive
* error 20004 dsDirtyDisk: request user to return a manually-ejected dirty disk
* error 20010 dsSCSIWarn: Portable SCSI adapter warning.
* error 20109 dsShutDownOrResume: allow user to return to Finder or ShutDown
* error 32767 dsSysErr: general system error