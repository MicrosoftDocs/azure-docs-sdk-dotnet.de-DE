<Type Name="IWithMessageBatching" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithMessageBatching">
  <TypeSignature Language="C#" Value="public interface IWithMessageBatching" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMessageBatching" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithMessageBatching" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMessageBatching" />
  <TypeSignature Language="F#" Value="type IWithMessageBatching = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase von der Warteschlange Definition ermöglicht konfigurieren Nachricht Batchverarbeitung Verhalten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMessageBatching">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithMessageBatching ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithMessageBatching() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithMessageBatching.WithMessageBatching" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMessageBatching () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithMessageBatching : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithMessageBatching.WithMessageBatching " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt an, dass mehrere Nachrichten, wenn es um oder Löschen von Nachrichten aus der internen Speicher schreiben Service Bus batch übergeben kann. Dies erhöht den Durchsatz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Warteschlange aktualisieren.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutMessageBatching">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithoutMessageBatching ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithoutMessageBatching() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithMessageBatching.WithoutMessageBatching" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutMessageBatching () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutMessageBatching : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithMessageBatching.WithoutMessageBatching " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt an, dass die Batchverarbeitung von Nachrichten sollte deaktiviert werden, wenn Service Bus schreiben Nachrichten oder Nachrichten aus der internen Speicher zu löschen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Warteschlange aktualisieren.</return>
      </Docs>
    </Member>
  </Members>
</Type>