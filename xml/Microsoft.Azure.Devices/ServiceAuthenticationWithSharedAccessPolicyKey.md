<Type Name="ServiceAuthenticationWithSharedAccessPolicyKey" FullName="Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyKey">
  <TypeSignature Language="C#" Value="public sealed class ServiceAuthenticationWithSharedAccessPolicyKey : Microsoft.Azure.Devices.IAuthenticationMethod" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceAuthenticationWithSharedAccessPolicyKey extends System.Object implements class Microsoft.Azure.Devices.IAuthenticationMethod" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyKey" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceAuthenticationWithSharedAccessPolicyKey&#xA;Implements IAuthenticationMethod" />
  <TypeSignature Language="F#" Value="type ServiceAuthenticationWithSharedAccessPolicyKey = class&#xA;    interface IAuthenticationMethod" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Devices.IAuthenticationMethod</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="603fb-101">Die Authentifizierungsmethode, die einen SAS-Richtlinienschlüssel verwendet.</span><span class="sxs-lookup"><span data-stu-id="603fb-101">Authentication method that uses a shared access policy key.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceAuthenticationWithSharedAccessPolicyKey (string policyName, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string policyName, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyKey.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (policyName As String, key As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyKey : string * string -&gt; Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyKey" Usage="new Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyKey (policyName, key)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policyName"><span data-ttu-id="603fb-102">Name der Richtlinie für freigegebenen Zugriff zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="603fb-102">Name of the shared access policy to use.</span></span></param>
        <param name="key"><span data-ttu-id="603fb-103">Schlüssel, die die SAS-Richtlinie zugeordnet werden.</span><span class="sxs-lookup"><span data-stu-id="603fb-103">Key associated with the shared access policy.</span></span></param>
        <summary>
            <span data-ttu-id="603fb-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyKey" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="603fb-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyKey" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public string Key { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyKey.Key" />
      <MemberSignature Language="VB.NET" Value="Public Property Key As String" />
      <MemberSignature Language="F#" Value="member this.Key : string with get, set" Usage="Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyKey.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyName">
      <MemberSignature Language="C#" Value="public string PolicyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyKey.PolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyName As String" />
      <MemberSignature Language="F#" Value="member this.PolicyName : string with get, set" Usage="Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyKey.PolicyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Populate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.IotHubConnectionStringBuilder Populate (Microsoft.Azure.Devices.IotHubConnectionStringBuilder iotHubConnectionStringBuilder);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IotHubConnectionStringBuilder Populate(class Microsoft.Azure.Devices.IotHubConnectionStringBuilder iotHubConnectionStringBuilder) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyKey.Populate(Microsoft.Azure.Devices.IotHubConnectionStringBuilder)" />
      <MemberSignature Language="F#" Value="abstract member Populate : Microsoft.Azure.Devices.IotHubConnectionStringBuilder -&gt; Microsoft.Azure.Devices.IotHubConnectionStringBuilder&#xA;override this.Populate : Microsoft.Azure.Devices.IotHubConnectionStringBuilder -&gt; Microsoft.Azure.Devices.IotHubConnectionStringBuilder" Usage="serviceAuthenticationWithSharedAccessPolicyKey.Populate iotHubConnectionStringBuilder" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Devices.IAuthenticationMethod.Populate(Microsoft.Azure.Devices.IotHubConnectionStringBuilder)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IotHubConnectionStringBuilder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="iotHubConnectionStringBuilder" Type="Microsoft.Azure.Devices.IotHubConnectionStringBuilder" />
      </Parameters>
      <Docs>
        <param name="iotHubConnectionStringBuilder">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>