<Type Name="ReminderSettings" FullName="Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings">
  <TypeSignature Language="C#" Value="public sealed class ReminderSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReminderSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReminderSettings" />
  <TypeSignature Language="F#" Value="type ReminderSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7d865-101">Diese Klasse stellt die Einstellungen, um das Verhalten von Erinnerungen zu konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="7d865-101">This class provides settings to configure the behavior of reminders.</span></span> <span data-ttu-id="7d865-102">Weitere Informationen finden Sie https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-reliable-actors-timers-reminders</span><span class="sxs-lookup"><span data-stu-id="7d865-102">See https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-reliable-actors-timers-reminders</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReminderSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7d865-103">Initialisiert eine neue Instanz der ReminderSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7d865-103">Initializes a new instance of the ReminderSettings class.</span></span>
            
            <span data-ttu-id="7d865-104">Standardmäßig die <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings.AutoDeleteOneTimeReminders" /> festgelegt ist, um <c>"true"</c>.</span><span class="sxs-lookup"><span data-stu-id="7d865-104">By default the <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings.AutoDeleteOneTimeReminders" /> is set to <c>true</c>.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOneTimeReminders">
      <MemberSignature Language="C#" Value="public bool AutoDeleteOneTimeReminders { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoDeleteOneTimeReminders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings.AutoDeleteOneTimeReminders" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOneTimeReminders As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOneTimeReminders : bool with get, set" Usage="Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings.AutoDeleteOneTimeReminders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7d865-105">Ruft ab oder legt ihn fest, der angibt, wenn ActorRuntime automatisch einmalige Erinnerungen löschen soll, nachdem sie ausgelöst und zugehörige Rückruf erfolgreich abgeschlossen haben.</span><span class="sxs-lookup"><span data-stu-id="7d865-105">Gets or sets value indicating if ActorRuntime should automatically delete one-time reminders after they have fired and completed its callback successfully.</span></span> <span data-ttu-id="7d865-106">Einmalige Erinnerungen finden Sie unter Hinweise zu deren <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.Period" /> negativer Wert festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="7d865-106">One-time reminders refer to reminders whose <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.Period" /> is set to negative value.</span></span>
            </summary>
        <value>
            <span data-ttu-id="7d865-107">Der Bool-Wert, der angibt, wenn ActorRuntime automatisch eine einmalige Erinnerungen löschen soll, nachdem er ausgelöst und zugehörige Rückruf erfolgreich abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="7d865-107">The bool value indicating if ActorRuntime should automatically delete a one-time reminders after it has fired and completed its callback successfully.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="7d865-108">Beachten Sie, die eine Erinnerung zu angesehen abgeschlossen erfolgreich nur, wenn Erinnerung Rückruf <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" /> erfolgreich abgeschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="7d865-108">Note that a reminder is considered to completed successfully only when reminder callback <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" /> completes successfully.</span></span>
            <span data-ttu-id="7d865-109">Wenn ein Failover erfolgt, während Erinnerung Rückruf ausgeführt wurde, werden die Erinnerung für neue primäre Replikat erneut ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="7d865-109">If a failover happens while reminder callback was executing, reminder will fire again on new primary replica.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>