<Type Name="ApplicationGatewayBackendHealthPool" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthPool">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayBackendHealthPool" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayBackendHealthPool extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthPool" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayBackendHealthPool" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayBackendHealthPool = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="26e36-101">Anwendungsgateway BackendHealth Pool.</span><span class="sxs-lookup"><span data-stu-id="26e36-101">Application gateway BackendHealth pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayBackendHealthPool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthPool.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="26e36-102">Initialisiert eine neue Instanz der ApplicationGatewayBackendHealthPool-Klasse.</span><span class="sxs-lookup"><span data-stu-id="26e36-102">Initializes a new instance of the ApplicationGatewayBackendHealthPool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayBackendHealthPool (Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool backendAddressPool = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings&gt; backendHttpSettingsCollection = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool backendAddressPool, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings&gt; backendHttpSettingsCollection) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthPool.#ctor(Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backendAddressPool As ApplicationGatewayBackendAddressPool = null, Optional backendHttpSettingsCollection As IList(Of ApplicationGatewayBackendHealthHttpSettings) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthPool : Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings&gt; -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthPool" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthPool (backendAddressPool, backendHttpSettingsCollection)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backendAddressPool" Type="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool" />
        <Parameter Name="backendHttpSettingsCollection" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings&gt;" />
      </Parameters>
      <Docs>
        <param name="backendAddressPool"><span data-ttu-id="26e36-103">Verweis auf eine Ressource ApplicationGatewayBackendAddressPool.</span><span class="sxs-lookup"><span data-stu-id="26e36-103">Reference of an ApplicationGatewayBackendAddressPool resource.</span></span></param>
        <param name="backendHttpSettingsCollection"><span data-ttu-id="26e36-104">Liste der ApplicationGatewayBackendHealthHttpSettings Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="26e36-104">List of ApplicationGatewayBackendHealthHttpSettings resources.</span></span></param>
        <summary>
            <span data-ttu-id="26e36-105">Initialisiert eine neue Instanz der ApplicationGatewayBackendHealthPool-Klasse.</span><span class="sxs-lookup"><span data-stu-id="26e36-105">Initializes a new instance of the ApplicationGatewayBackendHealthPool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendAddressPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool BackendAddressPool { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool BackendAddressPool" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthPool.BackendAddressPool" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendAddressPool As ApplicationGatewayBackendAddressPool" />
      <MemberSignature Language="F#" Value="member this.BackendAddressPool : Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthPool.BackendAddressPool" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backendAddressPool")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26e36-106">Ruft ab, oder legt ihn fest Verweis einer ApplicationGatewayBackendAddressPool Ressource.</span><span class="sxs-lookup"><span data-stu-id="26e36-106">Gets or sets reference of an ApplicationGatewayBackendAddressPool resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendHttpSettingsCollection">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings&gt; BackendHttpSettingsCollection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings&gt; BackendHttpSettingsCollection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthPool.BackendHttpSettingsCollection" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendHttpSettingsCollection As IList(Of ApplicationGatewayBackendHealthHttpSettings)" />
      <MemberSignature Language="F#" Value="member this.BackendHttpSettingsCollection : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthPool.BackendHttpSettingsCollection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backendHttpSettingsCollection")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26e36-107">Ruft ab oder legt die Liste der ApplicationGatewayBackendHealthHttpSettings Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="26e36-107">Gets or sets list of ApplicationGatewayBackendHealthHttpSettings resources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>