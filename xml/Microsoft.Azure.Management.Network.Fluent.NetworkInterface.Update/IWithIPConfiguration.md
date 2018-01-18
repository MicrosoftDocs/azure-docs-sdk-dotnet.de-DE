<Type Name="IWithIPConfiguration" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithIPConfiguration">
  <TypeSignature Language="C#" Value="public interface IWithIPConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIPConfiguration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithIPConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIPConfiguration" />
  <TypeSignature Language="F#" Value="type IWithIPConfiguration = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9124b-101">Die Phase des Netzwerk-Schnittstelle Updates so konfigurieren Sie die IP-Konfiguration ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="9124b-101">The stage of the network interface update allowing to configure IP configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineSecondaryIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate&gt; DefineSecondaryIPConfiguration (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate&gt; DefineSecondaryIPConfiguration(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithIPConfiguration.DefineSecondaryIPConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSecondaryIPConfiguration (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineSecondaryIPConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate&gt;" Usage="iWithIPConfiguration.DefineSecondaryIPConfiguration name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="9124b-102">Der Name für die IP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="9124b-102">Name for the IP configuration.</span></span></param>
        <summary>
            <span data-ttu-id="9124b-103">Startet die Definition für eine sekundäre IP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="9124b-103">Starts definition of a secondary IP configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9124b-104">Die erste Stufe der Definition eines sekundäre IP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="9124b-104">The first stage of a secondary IP configuration definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate UpdateIPConfiguration (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate UpdateIPConfiguration(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithIPConfiguration.UpdateIPConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateIPConfiguration (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateIPConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate" Usage="iWithIPConfiguration.UpdateIPConfiguration name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="9124b-105">Der Name der IP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="9124b-105">Name of the IP configuration.</span></span></param>
        <summary>
            <span data-ttu-id="9124b-106">Startet ein update des IP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="9124b-106">Starts update of an IP configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9124b-107">die erste Phase eines Updates der IP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="9124b-107">The first stage of an IP configuration update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithoutIPConfiguration (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithoutIPConfiguration(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithIPConfiguration.WithoutIPConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutIPConfiguration (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutIPConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithIPConfiguration.WithoutIPConfiguration name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>