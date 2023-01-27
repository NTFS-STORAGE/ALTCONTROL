game.Players.PlayerChatted:Connect(function(ChatType, PlayerWhoSentMsg, Msg, RecipientIfMsgIsPM) 
    print(("%s just said '%s'"):format(PlayerWhoSentMsg.name, Msg))
    
    if Msg:sub(1,4) == ";cmd" then
        -- do whatever
    elseif Msg:sub(1,5) == ";help" then
        -- do whatever
    -- etc.
    end
end)
