const Discord = require('discord.js');

module.exports = {
    name: "핑", //여기에 자신이 원하는 명령어를 넣고

    execute(message,args){ //여기 안에 ping 이라는 명령어가 실행 되었을때 실행할 코드를 입력 해주시면 됩니다!

        const ping = new Discord.MessageEmbed()
        .setDescription(`🏓\`${Date.now() - message.createdTimestamp}\`ms 입니다!`);

        
        message.channel.send(ping); //마지막에는 ping을 보냅니다
    }
    
