
            elif -60 < delta <= 0:
                await channel.send(f"🎉 {boss} 已重生囉，快集合！")
        except Exception as e:
            print(f"提醒失敗：{boss} → {e}")

bot.run(TOKEN)
