# differentialprivacy-
{ "version": 21, "segments": [ { "algorithm": "CountMedianSketch", "key": "com.apple.keyboard.Emoji.en_US.EmojiKeyboard", "parameters": {"epsilon":4,"k":65536,"m":1024}, "records": [ "55908,802200204201000000020102100008101100100245218B02C2089014000810128A2400008000002810002000A000008442400010004000024D009000000000000004001008041000080000208000000B008000410100012004444800C4000000010080220300C000000000200008002200043024820061004600810040800000" ] }, { "algorithm": "CountMedianSketch", "key": "com.apple.screentime.usagetracking.UnknownDomain", "parameters": {"epsilon":8,"k":65536,"m":1024}, "records": [ "54816,0000000000000000080010000000000800000040000400020000000000000000040000000000000000400000000000000000190000000800840000000080200000000000010008000000000000000000000000000400100000000000000008000000000100000000800080000000000000000004000080000000000000000000" ] }, { "algorithm": "CountMedianSketch", "key": "com.apple.keyboard.RevisedWords.en_US", "parameters": {"epsilon":8,"k":65536,"m":1024}, "records": [ "34666,0000000000000001000000000000000000000000000000000000000000040800000000000000000000000000000000800000000000000100000000004000000000000040000000000000000000000000000080000000000000040000000001000040000800000000000000000400000000000000020000000A00000000000000" ] }, { "algorithm": "SequenceFragmentPuzzle+CountMedianSketch", "key": "com.apple.keyboard.NewWords.en_US", "parameters": {"puzzleCount":256,"fragmentCount":5,"fragmentWidth":2,"fragmentK":2048,"epsilon":8,"sequenceFragmentBias":0.25,"sequenceM":1024,"fragmentM":1024,"sequenceK":2048}, "records": [ "264,08049006055A0680402C002008184032144C428980100C8802022008220520019C0520C800B10C108200CE288309420B00E400200810048031B101484B2908704720011A0120121053011014589801101120A8E80E81A02410594302D802200E0505A0053272A9970A14592004159024400A900848A5941F5342403CC8D33920,3,1634,4400000000030004000000000000000000020010808000000000000000000000000008080000000001000000000000400000000100400000040200000001000010000A00801210002000814800100000200040200000000002401000000000000000000000000002400600800000002000000000000800008000600200000000", "561,0662217820C34E41200492158508020034DC451026442021000090500805102C2262700089816AC214024822A2140121000800A038285071000A1262202B74860414A8110041918732056002A40A701B190035A420C540A0025052001112108800301E48C6113180088241405E5851479102961C01CD0040200403B9810A1188,5,1046,98000200000108404000000000000800400110428000030002000000000000001004008080000080002000000000000000000100084000006040C00001010C8000000000080000001440840020000000000000000000420000000000000080000000000800000400040004000000000000000000008020008000012100200200" ] }, { "algorithm": "CountMedianSketch", "key": "com.apple.mail.SenderDomain.en_US", "parameters": {"epsilon":8,"k":65536,"m":1024}, "records": [ "1107,0000000000108000400000000008000040008000000000000002000000000000000000000000000000400000000000000000000000000000000002000000000800000008008000000000000080000000000010000000000000000000000021000100000020000000000000800010000000000000000002000000000000000000" ] }, { "algorithm": "HadamardCountMedianSketch", "key": "com.apple.safari.DomainVisited", "parameters": {"epsilon":4,"k":1024,"m":32768}, "records": [ "814,5596,+1" ] } ] }
