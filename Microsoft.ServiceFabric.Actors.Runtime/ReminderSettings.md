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
            Diese Klasse stellt die Einstellungen, um das Verhalten von Erinnerungen zu konfigurieren. Weitere Informationen finden Sie https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-reliable-actors-timers-reminders
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
            Initialisiert eine neue Instanz der ReminderSettings-Klasse.
            
            Standardmäßig die <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings.AutoDeleteOneTimeReminders" /> festgelegt ist, um <c>"true"</c>.
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
            Ruft ab oder legt ihn fest, der angibt, wenn ActorRuntime automatisch einmalige Erinnerungen löschen soll, nachdem sie ausgelöst und zugehörige Rückruf erfolgreich abgeschlossen haben. Einmalige Erinnerungen finden Sie unter Hinweise zu deren <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.Period" /> negativer Wert festgelegt ist.
            </summary>
        <value>
            Der Bool-Wert, der angibt, wenn ActorRuntime automatisch eine einmalige Erinnerungen löschen soll, nachdem er ausgelöst und zugehörige Rückruf erfolgreich abgeschlossen wurde.
            </value>
        <remarks>
            Beachten Sie, die eine Erinnerung zu angesehen abgeschlossen erfolgreich nur, wenn Erinnerung Rückruf <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" /> erfolgreich abgeschlossen wird.
            Wenn ein Failover erfolgt, während Erinnerung Rückruf ausgeführt wurde, werden die Erinnerung für neue primäre Replikat erneut ausgelöst.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>