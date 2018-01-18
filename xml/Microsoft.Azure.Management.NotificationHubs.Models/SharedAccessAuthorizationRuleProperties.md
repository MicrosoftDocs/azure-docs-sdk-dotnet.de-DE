<Type Name="SharedAccessAuthorizationRuleProperties" FullName="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties">
  <TypeSignature Language="C#" Value="public class SharedAccessAuthorizationRuleProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedAccessAuthorizationRuleProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedAccessAuthorizationRuleProperties" />
  <TypeSignature Language="F#" Value="type SharedAccessAuthorizationRuleProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c3af2-101">SharedAccessAuthorizationRule-Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="c3af2-101">SharedAccessAuthorizationRule properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAuthorizationRuleProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c3af2-102">Initialisiert eine neue Instanz der SharedAccessAuthorizationRuleProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c3af2-102">Initializes a new instance of the SharedAccessAuthorizationRuleProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAuthorizationRuleProperties (System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.AccessRights&gt;&gt; rights = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.NotificationHubs.Models.AccessRights&gt;&gt; rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties.#ctor(System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.NotificationHubs.Models.AccessRights}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional rights As IList(Of Nullable(Of AccessRights)) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.AccessRights&gt;&gt; -&gt; Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties rights" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rights" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.AccessRights&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="rights"><span data-ttu-id="c3af2-103">Die Rechte, die in der Regel zugeordneten.</span><span class="sxs-lookup"><span data-stu-id="c3af2-103">The rights associated with the rule.</span></span></param>
        <summary>
            <span data-ttu-id="c3af2-104">Initialisiert eine neue Instanz der SharedAccessAuthorizationRuleProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c3af2-104">Initializes a new instance of the SharedAccessAuthorizationRuleProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rights">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.AccessRights&gt;&gt; Rights { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.NotificationHubs.Models.AccessRights&gt;&gt; Rights" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties.Rights" />
      <MemberSignature Language="VB.NET" Value="Public Property Rights As IList(Of Nullable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="member this.Rights : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.AccessRights&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties.Rights" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rights")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.AccessRights&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3af2-105">Ruft ab oder legt die Berechtigungen, die in der Regel zugeordneten.</span><span class="sxs-lookup"><span data-stu-id="c3af2-105">Gets or sets the rights associated with the rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>