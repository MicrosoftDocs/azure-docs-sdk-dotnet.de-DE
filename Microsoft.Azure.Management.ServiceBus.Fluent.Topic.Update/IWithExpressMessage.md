<Type Name="IWithExpressMessage" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithExpressMessage">
  <TypeSignature Language="C#" Value="public interface IWithExpressMessage" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExpressMessage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithExpressMessage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExpressMessage" />
  <TypeSignature Language="F#" Value="type IWithExpressMessage = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase die festlegen, dass es entweder als markieren themadefinition halten regelmäßigen oder express-Nachrichten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExpressMessage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithExpressMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithExpressMessage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithExpressMessage.WithExpressMessage" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExpressMessage () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExpressMessage : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate" Usage="iWithExpressMessage.WithExpressMessage " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt an, dass Nachrichten in diesem Thema express daher, dass sie für einige Zeit, bevor sie in der messagingspeicher gespeichert im Arbeitsspeicher zwischengespeichert werden können.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Topics aktualisieren.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutExpressMessage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithoutExpressMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithoutExpressMessage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithExpressMessage.WithoutExpressMessage" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutExpressMessage () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutExpressMessage : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate" Usage="iWithExpressMessage.WithoutExpressMessage " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt an, dass Nachrichten in diesem Thema keine ausdrückliche daher, dass sie im Arbeitsspeicher zwischengespeichert werden sollen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Topics aktualisieren.</return>
      </Docs>
    </Member>
  </Members>
</Type>