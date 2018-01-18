<Type Name="IWithSourcePort" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourcePort">
  <TypeSignature Language="C#" Value="public interface IWithSourcePort" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSourcePort" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourcePort" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSourcePort" />
  <TypeSignature Language="F#" Value="type IWithSourcePort = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2e1dc-101">Die Stufe der Beschreibung der Netzwerk-Regel ermöglicht die Quelle-Ports angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="2e1dc-101">The stage of the network rule description allowing the source port(s) to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromAnyPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate FromAnyPort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate FromAnyPort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourcePort.FromAnyPort" />
      <MemberSignature Language="VB.NET" Value="Public Function FromAnyPort () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member FromAnyPort : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithSourcePort.FromAnyPort " />
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
            <span data-ttu-id="2e1dc-102">Macht diese Regel auf einem beliebigen Quellport angewendet.</span><span class="sxs-lookup"><span data-stu-id="2e1dc-102">Makes this rule apply to any source port.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2e1dc-103">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="2e1dc-103">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="FromPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate FromPort (int port);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate FromPort(int32 port) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourcePort.FromPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromPort (port As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member FromPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithSourcePort.FromPort port" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="port" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="port"><span data-ttu-id="2e1dc-104">Die Quellportnummer an.</span><span class="sxs-lookup"><span data-stu-id="2e1dc-104">The source port number.</span></span></param>
        <summary>
            <span data-ttu-id="2e1dc-105">Gibt den Quellport für den diese Regel gilt.</span><span class="sxs-lookup"><span data-stu-id="2e1dc-105">Specifies the source port to which this rule applies.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2e1dc-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="2e1dc-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="FromPortRange">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate FromPortRange (int from, int to);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate FromPortRange(int32 from, int32 to) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourcePort.FromPortRange(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromPortRange (from As Integer, to As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member FromPortRange : int * int -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithSourcePort.FromPortRange (from, to)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.Int32" />
        <Parameter Name="to" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="from"><span data-ttu-id="2e1dc-107">Die erste Portnummer.</span><span class="sxs-lookup"><span data-stu-id="2e1dc-107">The starting port number.</span></span></param>
        <param name="to"><span data-ttu-id="2e1dc-108">Die letzte Portnummer.</span><span class="sxs-lookup"><span data-stu-id="2e1dc-108">The ending port number.</span></span></param>
        <summary>
            <span data-ttu-id="2e1dc-109">Gibt an, der Quellportbereich für die diese Regel gilt.</span><span class="sxs-lookup"><span data-stu-id="2e1dc-109">Specifies the source port range to which this rule applies.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2e1dc-110">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="2e1dc-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>