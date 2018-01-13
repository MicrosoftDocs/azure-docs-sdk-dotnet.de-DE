<Type Name="IWithMessageLockDuration" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageLockDuration">
  <TypeSignature Language="C#" Value="public interface IWithMessageLockDuration" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMessageLockDuration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageLockDuration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMessageLockDuration" />
  <TypeSignature Language="F#" Value="type IWithMessageLockDuration = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Abonnementdefinition, sodass Dauer für eine nachrichtensperre zu definieren.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMessageLockDurationInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate WithMessageLockDurationInSeconds (int durationInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate WithMessageLockDurationInSeconds(int32 durationInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageLockDuration.WithMessageLockDurationInSeconds(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMessageLockDurationInSeconds (durationInSeconds As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithMessageLockDurationInSeconds : int -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate" Usage="iWithMessageLockDuration.WithMessageLockDurationInSeconds durationInSeconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="durationInSeconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="durationInSeconds">Die Dauer der Sperre in Sekunden.</param>
        <summary>
            Gibt die Zeitspanne, die die Nachricht für andere Empfänger gesperrt ist.
            Hinweis: es sei denn, sie explizit außer Kraft gesetzt wird die sperrenstandarddauer beträgt 60 Sekunden an, der maximal zulässige Wert beträgt 300 Sekunden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Abonnementdefinition.</return>
      </Docs>
    </Member>
  </Members>
</Type>