# WebMAlphaSample
透過のWebMファイルのサンプル

## WebMファイルの作成方法
FFmpeg をインストールした環境で以下のコマンドを実行

### VP8 コーデックを使う場合
`
ffmpeg -r 30 -i Images/frame%04d.png -auto-alt-ref 0 -c:v libvpx sample_vp8.webm
`

### VP9 コーデックを使う場合
`
ffmpeg -r 30 -i Images/frame%04d.png -auto-alt-ref 0 sample_vp9.webm
`
