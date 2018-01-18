<Type Name="IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount">
  <TypeSignature Language="C#" Value="public interface IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount" />
  <TypeSignature Language="F#" Value="type IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="49cc4-101">Die Phase der Abonnementdefinition ermöglicht maximale Übermittlungsanzahl Nachricht vor dem Verschieben an Dead Letter-Warteschlange angeben.</span><span class="sxs-lookup"><span data-stu-id="49cc4-101">The stage of the subscription definition allowing to specify maximum delivery count of message before moving it to dead-letter queue.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount (int deliveryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount(int32 deliveryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount.WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount (deliveryCount As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount : int -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate" Usage="iWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount.WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount deliveryCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deliveryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="deliveryCount"><span data-ttu-id="49cc4-102">Maximaler Zustellungen-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="49cc4-102">Maximum delivery subscription.</span></span></param>
        <summary>
            <span data-ttu-id="49cc4-103">Gibt die maximale Anzahl der Häufigkeit, mit die eine Nachricht übermittelt werden kann.</span><span class="sxs-lookup"><span data-stu-id="49cc4-103">Specifies maximum number of times a message can be delivered.</span></span> <span data-ttu-id="49cc4-104">Sobald diese Anzahl überschritten wurde, wird Nachricht unzustellbare Abonnement verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="49cc4-104">Once this count has exceeded, message will be moved to dead-letter subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="49cc4-105">Die nächste Phase der Update-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="49cc4-105">The next stage of subscription update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>