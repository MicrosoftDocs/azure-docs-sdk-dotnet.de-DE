<Type Name="RedisFirewallRuleCreateParameters" FullName="Microsoft.Azure.Management.Redis.Models.RedisFirewallRuleCreateParameters">
  <TypeSignature Language="C#" Value="public class RedisFirewallRuleCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedisFirewallRuleCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Models.RedisFirewallRuleCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class RedisFirewallRuleCreateParameters" />
  <TypeSignature Language="F#" Value="type RedisFirewallRuleCreateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ed51f-101">Für das Erstellen einer Firewallregel auf erforderliche Parameter redis-Cache.</span><span class="sxs-lookup"><span data-stu-id="ed51f-101">Parameters required for creating a firewall rule on redis cache.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisFirewallRuleCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisFirewallRuleCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ed51f-102">Initialisiert eine neue Instanz der RedisFirewallRuleCreateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ed51f-102">Initializes a new instance of the RedisFirewallRuleCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisFirewallRuleCreateParameters (string startIP, string endIP);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string startIP, string endIP) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisFirewallRuleCreateParameters.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (startIP As String, endIP As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Models.RedisFirewallRuleCreateParameters : string * string -&gt; Microsoft.Azure.Management.Redis.Models.RedisFirewallRuleCreateParameters" Usage="new Microsoft.Azure.Management.Redis.Models.RedisFirewallRuleCreateParameters (startIP, endIP)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startIP" Type="System.String" />
        <Parameter Name="endIP" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="startIP"><span data-ttu-id="ed51f-103">niedrigste IP-Adresse im Bereich enthalten</span><span class="sxs-lookup"><span data-stu-id="ed51f-103">lowest IP address included in the range</span></span></param>
        <param name="endIP"><span data-ttu-id="ed51f-104">höchste IP-Adresse im Bereich enthalten</span><span class="sxs-lookup"><span data-stu-id="ed51f-104">highest IP address included in the range</span></span></param>
        <summary>
            <span data-ttu-id="ed51f-105">Initialisiert eine neue Instanz der RedisFirewallRuleCreateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ed51f-105">Initializes a new instance of the RedisFirewallRuleCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndIP">
      <MemberSignature Language="C#" Value="public string EndIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisFirewallRuleCreateParameters.EndIP" />
      <MemberSignature Language="VB.NET" Value="Public Property EndIP As String" />
      <MemberSignature Language="F#" Value="member this.EndIP : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisFirewallRuleCreateParameters.EndIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endIP")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ed51f-106">Ruft ab oder legt die höchste IP-Adresse im Bereich enthalten</span><span class="sxs-lookup"><span data-stu-id="ed51f-106">Gets or sets highest IP address included in the range</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartIP">
      <MemberSignature Language="C#" Value="public string StartIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisFirewallRuleCreateParameters.StartIP" />
      <MemberSignature Language="VB.NET" Value="Public Property StartIP As String" />
      <MemberSignature Language="F#" Value="member this.StartIP : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisFirewallRuleCreateParameters.StartIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startIP")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ed51f-107">Ruft ab oder legt die niedrigste IP-Adresse im Bereich enthalten</span><span class="sxs-lookup"><span data-stu-id="ed51f-107">Gets or sets lowest IP address included in the range</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisFirewallRuleCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="redisFirewallRuleCreateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ed51f-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="ed51f-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ed51f-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="ed51f-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>