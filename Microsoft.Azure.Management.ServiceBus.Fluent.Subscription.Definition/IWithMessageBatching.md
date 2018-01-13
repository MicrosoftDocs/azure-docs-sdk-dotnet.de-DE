<Type Name="IWithMessageBatching" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageBatching">
  <TypeSignature Language="C#" Value="public interface IWithMessageBatching" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMessageBatching" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageBatching" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMessageBatching" />
  <TypeSignature Language="F#" Value="type IWithMessageBatching = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der dem Abonnement Definition ermöglicht geben Batchverarbeitung Verhalten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutMessageBatching">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate WithoutMessageBatching ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate WithoutMessageBatching() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageBatching.WithoutMessageBatching" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutMessageBatching () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithoutMessageBatching : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate" Usage="iWithMessageBatching.WithoutMessageBatching " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt an, dass die Standard-Batchverarbeitung für dieses Abonnement deaktiviert werden soll.
            Mit der Batchverarbeitung Dienst kann Bus Nachricht mehrere Batches, beim Schreiben oder Löschen von Nachrichten aus der internen Speicher.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Abonnementdefinition.</return>
      </Docs>
    </Member>
  </Members>
</Type>