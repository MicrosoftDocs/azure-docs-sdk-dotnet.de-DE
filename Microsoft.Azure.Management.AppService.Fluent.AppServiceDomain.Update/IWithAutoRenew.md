<Type Name="IWithAutoRenew" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IWithAutoRenew">
  <TypeSignature Language="C#" Value="public interface IWithAutoRenew" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAutoRenew" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IWithAutoRenew" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAutoRenew" />
  <TypeSignature Language="F#" Value="type IWithAutoRenew = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8a466-101">Eine Domäne Definition ermöglicht automatische Verlängerung Einstellung festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="8a466-101">A domain definition allowing auto-renew setting to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAutoRenewEnabled">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IUpdate WithAutoRenewEnabled (bool autoRenew);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IUpdate WithAutoRenewEnabled(bool autoRenew) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IWithAutoRenew.WithAutoRenewEnabled(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAutoRenewEnabled (autoRenew As Boolean) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithAutoRenewEnabled : bool -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IUpdate" Usage="iWithAutoRenew.WithAutoRenewEnabled autoRenew" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="autoRenew" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="autoRenew"><span data-ttu-id="8a466-102">"True", wenn die Domäne automatisch erneuert werden soll.</span><span class="sxs-lookup"><span data-stu-id="8a466-102">True if the domain should be automatically renewed.</span></span></param>
        <summary>
            <span data-ttu-id="8a466-103">Gibt an, ob die Domäne automatisch erneuert werden soll, wenn er ist bald abgelaufen.</span><span class="sxs-lookup"><span data-stu-id="8a466-103">Specifies if the domain should be automatically renewed when it's about to expire.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8a466-104">die nächste Phase der Domänendefinition.</span><span class="sxs-lookup"><span data-stu-id="8a466-104">The next stage of domain definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>