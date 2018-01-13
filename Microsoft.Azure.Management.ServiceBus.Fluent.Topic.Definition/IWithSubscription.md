<Type Name="IWithSubscription" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithSubscription">
  <TypeSignature Language="C#" Value="public interface IWithSubscription" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSubscription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithSubscription" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSubscription" />
  <TypeSignature Language="F#" Value="type IWithSubscription = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Service Bus Namespace Update Möglichkeit zum Verwalten von Abonnements für das Thema.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate WithNewSubscription (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate WithNewSubscription(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithSubscription.WithNewSubscription(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewSubscription (name As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewSubscription : string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate" Usage="iWithSubscription.WithNewSubscription name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Warteschlange.</param>
        <summary>
            Erstellt eine abonnemententität für das Service Bus-Thema.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der themadefinition.</return>
      </Docs>
    </Member>
  </Members>
</Type>