<Type Name="IWithExpiredMessageMovedToDeadLetterSubscription" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithExpiredMessageMovedToDeadLetterSubscription">
  <TypeSignature Language="C#" Value="public interface IWithExpiredMessageMovedToDeadLetterSubscription" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExpiredMessageMovedToDeadLetterSubscription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithExpiredMessageMovedToDeadLetterSubscription" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExpiredMessageMovedToDeadLetterSubscription" />
  <TypeSignature Language="F#" Value="type IWithExpiredMessageMovedToDeadLetterSubscription = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d950c-101">Die Stufe der Abonnement Update ermöglicht angeben, ob die ablaufmeldung für eine sekundäre unzustellbare Abonnement verschoben werden kann.</span><span class="sxs-lookup"><span data-stu-id="d950c-101">The stage of the subscription update allowing to specify whether expired message can be moved to secondary dead-letter subscription.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExpiredMessageMovedToDeadLetterSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithExpiredMessageMovedToDeadLetterSubscription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithExpiredMessageMovedToDeadLetterSubscription() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithExpiredMessageMovedToDeadLetterSubscription.WithExpiredMessageMovedToDeadLetterSubscription" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExpiredMessageMovedToDeadLetterSubscription () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExpiredMessageMovedToDeadLetterSubscription : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate" Usage="iWithExpiredMessageMovedToDeadLetterSubscription.WithExpiredMessageMovedToDeadLetterSubscription " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d950c-102">Gibt an, die abgelaufene Nachricht unzustellbare Abonnement verschoben werden muss.</span><span class="sxs-lookup"><span data-stu-id="d950c-102">Specifies that expired message must be moved to dead-letter subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d950c-103">Die nächste Phase der Update-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="d950c-103">The next stage of subscription update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutExpiredMessageMovedToDeadLetterSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithoutExpiredMessageMovedToDeadLetterSubscription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithoutExpiredMessageMovedToDeadLetterSubscription() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithExpiredMessageMovedToDeadLetterSubscription.WithoutExpiredMessageMovedToDeadLetterSubscription" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutExpiredMessageMovedToDeadLetterSubscription () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutExpiredMessageMovedToDeadLetterSubscription : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate" Usage="iWithExpiredMessageMovedToDeadLetterSubscription.WithoutExpiredMessageMovedToDeadLetterSubscription " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d950c-104">Gibt an, die abgelaufene Nachricht unzustellbare Abonnement nicht verschoben werden soll.</span><span class="sxs-lookup"><span data-stu-id="d950c-104">Specifies that expired message should not be moved to dead-letter subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d950c-105">Die nächste Phase der Update-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="d950c-105">The next stage of subscription update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>