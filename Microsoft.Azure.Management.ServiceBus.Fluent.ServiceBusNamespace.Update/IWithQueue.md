<Type Name="IWithQueue" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IWithQueue">
  <TypeSignature Language="C#" Value="public interface IWithQueue" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithQueue" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IWithQueue" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithQueue" />
  <TypeSignature Language="F#" Value="type IWithQueue = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Service Bus Namespace Update Möglichkeit zum Verwalten von Warteschlangen im Namespace.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewQueue">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate WithNewQueue (string name, int maxSizeInMB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate WithNewQueue(string name, int32 maxSizeInMB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IWithQueue.WithNewQueue(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewQueue (name As String, maxSizeInMB As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewQueue : string * int -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate" Usage="iWithQueue.WithNewQueue (name, maxSizeInMB)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="maxSizeInMB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Warteschlange.</param>
        <param name="maxSizeInMB">Maximale Größe des Arbeitsspeichers für die warteschlangenentität.</param>
        <summary>
            Erstellt eine warteschlangenentität in Service Bus-Namespace an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Nächste Phase der Service Bus-Namespace aktualisieren.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutQueue">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate WithoutQueue (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate WithoutQueue(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IWithQueue.WithoutQueue(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutQueue (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutQueue : string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate" Usage="iWithQueue.WithoutQueue name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Warteschlange.</param>
        <summary>
            Entfernt eine warteschlangenentität aus dem Service Bus-Namespace an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Nächste Phase der Service Bus-Namespace aktualisieren.</return>
      </Docs>
    </Member>
  </Members>
</Type>