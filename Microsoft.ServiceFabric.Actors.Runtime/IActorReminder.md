<Type Name="IActorReminder" FullName="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder">
  <TypeSignature Language="C#" Value="public interface IActorReminder" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorReminder" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorReminder" />
  <TypeSignature Language="F#" Value="type IActorReminder = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Erinnerung mit registriert <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.RegisterReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DueTime">
      <MemberSignature Language="C#" Value="public TimeSpan DueTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DueTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.DueTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DueTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DueTime : TimeSpan" Usage="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.DueTime" />
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
            Ruft die Uhrzeit für die Erinnerung aufgrund einer ersten, aufgerufen werden soll.
            </summary>
        <value>Die Uhrzeit für die Erinnerung aufgrund einer ersten, aufgerufen werden soll.</value>
        <remarks>
            Ein Wert von (-1) Millisekunden bedeutet, dass die Erinnerung nicht aufgerufen wird. Der Wert NULL (0) bedeutet, wenn die Erinnerung sofort nach der Registrierung aufgerufen wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen der Erinnerung ab. Der Name ist eindeutig pro Akteur.
            </summary>
        <value>Der Name der Erinnerung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Period">
      <MemberSignature Language="C#" Value="public TimeSpan Period { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan Period" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.Period" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Period As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.Period : TimeSpan" Usage="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.Period" />
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
            Ruft das Zeitintervall an, an dem die Erinnerung in regelmäßigen Abständen aufgerufen wird.
            </summary>
        <value>Das Zeitintervall, an dem die Erinnerung in regelmäßigen Abständen aufgerufen wird.</value>
        <remarks>
            Der erste Aufruf der Erinnerung tritt ein, nachdem <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.DueTime" />. Alle nachfolgenden Aufrufe erfolgen in Abständen, die von dieser Eigenschaft definiert.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public byte[] State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Byte()" />
      <MemberSignature Language="F#" Value="member this.State : byte[]" Usage="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Benutzerzustand, der für die Erinnerung-Aufruf übergeben.
            </summary>
        <value>Der Benutzerzustand für den Aufruf Erinnerung übergeben.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>