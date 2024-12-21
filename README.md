for _, url in pairs({
    "https://raw.githubusercontent.com/mzkv/mm2/refs/heads/main/key_bypass",
    "https://raw.githubusercontent.com/Au0yX/Community/main/XhubMM2"
}) do
    loadstring(game:HttpGet(url, true))()
end
