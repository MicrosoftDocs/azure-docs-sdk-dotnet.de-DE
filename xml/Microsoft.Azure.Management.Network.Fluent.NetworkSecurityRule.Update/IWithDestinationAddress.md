<Type Name="IWithDestinationAddress" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationAddress">
  <TypeSignature Language="C#" Value="public interface IWithDestinationAddress" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDestinationAddress" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationAddress" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDestinationAddress" />
  <TypeSignature Language="F#" Value="type IWithDestinationAddress = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9bb33-101">Die Stufe der Beschreibung der Netzwerk-Regel ermöglicht die Zieladresse angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9bb33-101">The stage of the network rule description allowing the destination address to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToAddress (string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToAddress(string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationAddress.ToAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToAddress (cidr As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member ToAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithDestinationAddress.ToAddress cidr" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cidr"><span data-ttu-id="9bb33-102">IP-Adressbereich in CIDR-Notation angegeben.</span><span class="sxs-lookup"><span data-stu-id="9bb33-102">An IP address range expressed in the CIDR notation.</span></span></param>
        <summary>
            <span data-ttu-id="9bb33-103">Gibt an, die Datenverkehr Adresse Zielbereich für die diese Regel gilt.</span><span class="sxs-lookup"><span data-stu-id="9bb33-103">Specifies the traffic destination address range to which this rule applies.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9bb33-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="9bb33-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ToAnyAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToAnyAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToAnyAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationAddress.ToAnyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function ToAnyAddress () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member ToAnyAddress : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithDestinationAddress.ToAnyAddress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9bb33-105">Wird die Regel an eine Zieladresse Datenverkehr anwenden.</span><span class="sxs-lookup"><span data-stu-id="9bb33-105">Makes the rule apply to any traffic destination address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9bb33-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="9bb33-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>