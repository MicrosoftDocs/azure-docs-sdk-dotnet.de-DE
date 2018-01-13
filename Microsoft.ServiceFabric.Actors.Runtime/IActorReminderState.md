<Type Name="IActorReminderState" FullName="Microsoft.ServiceFabric.Actors.Runtime.IActorReminderState">
  <TypeSignature Language="C#" Value="public interface IActorReminderState : Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorReminderState implements class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.IActorReminderState" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorReminderState&#xA;Implements IActorReminder" />
  <TypeSignature Language="F#" Value="type IActorReminderState = interface&#xA;    interface IActorReminder" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Actors.Runtime.IActorReminder</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt die internen Zustand des Akteurs Erinnerung dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="RemainingDueTime">
      <MemberSignature Language="C#" Value="public TimeSpan RemainingDueTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RemainingDueTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminderState.RemainingDueTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemainingDueTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RemainingDueTime : TimeSpan" Usage="Microsoft.ServiceFabric.Actors.Runtime.IActorReminderState.RemainingDueTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Uhrzeit für die Erinnerung aufgrund weiter.
            </summary>
        <value>Vorlaufzeit als <see cref="T:System.TimeSpan" /> Wenn die Erinnerung geht es weiter? fällig.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>