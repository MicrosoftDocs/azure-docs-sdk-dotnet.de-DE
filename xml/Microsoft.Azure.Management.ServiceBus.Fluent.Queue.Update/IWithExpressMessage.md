<Type Name="IWithExpressMessage" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithExpressMessage">
  <TypeSignature Language="C#" Value="public interface IWithExpressMessage" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExpressMessage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithExpressMessage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExpressMessage" />
  <TypeSignature Language="F#" Value="type IWithExpressMessage = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9a501-101">Die Phase die Warteschlangendefinition festlegen, dass es entweder als markieren halten regelmäßigen oder express-Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="9a501-101">The stage of the queue definition allowing to mark it as either holding regular or express messages.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExpressMessage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithExpressMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithExpressMessage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithExpressMessage.WithExpressMessage" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExpressMessage () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExpressMessage : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithExpressMessage.WithExpressMessage " />
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
            <span data-ttu-id="9a501-102">Gibt an, dass Nachrichten in dieser Warteschlange express daher, dass sie für einige Zeit, bevor sie in der messagingspeicher gespeichert im Arbeitsspeicher zwischengespeichert werden können.</span><span class="sxs-lookup"><span data-stu-id="9a501-102">Specifies that messages in this queue are express hence they can be cached in memory for some time before storing it in messaging store.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9a501-103">Die nächste Phase der Warteschlange aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="9a501-103">The next stage of queue update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutExpressMessage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithoutExpressMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithoutExpressMessage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithExpressMessage.WithoutExpressMessage" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutExpressMessage () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutExpressMessage : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithExpressMessage.WithoutExpressMessage " />
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
            <span data-ttu-id="9a501-104">Gibt an, dass Nachrichten in dieser Warteschlange nicht express daher, dass sie im Arbeitsspeicher zwischengespeichert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="9a501-104">Specifies that messages in this queue are not express hence they should be cached in memory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9a501-105">Die nächste Phase der Warteschlange aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="9a501-105">The next stage of queue update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>