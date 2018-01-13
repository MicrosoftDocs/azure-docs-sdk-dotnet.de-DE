<Type Name="AuthorizationRuleProperties" FullName="Microsoft.Azure.Management.ServiceBus.Models.AuthorizationRuleProperties">
  <TypeSignature Language="C#" Value="public class AuthorizationRuleProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AuthorizationRuleProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.AuthorizationRuleProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class AuthorizationRuleProperties" />
  <TypeSignature Language="F#" Value="type AuthorizationRuleProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            AuthorizationRule-Eigenschaften.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationRuleProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.AuthorizationRuleProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AuthorizationRuleProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationRuleProperties (System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessRights&gt;&gt; rights);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.AccessRights&gt;&gt; rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.AuthorizationRuleProperties.#ctor(System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.ServiceBus.Models.AccessRights}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (rights As IList(Of Nullable(Of AccessRights)))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.AuthorizationRuleProperties : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessRights&gt;&gt; -&gt; Microsoft.Azure.Management.ServiceBus.Models.AuthorizationRuleProperties" Usage="new Microsoft.Azure.Management.ServiceBus.Models.AuthorizationRuleProperties rights" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rights" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessRights&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="rights">Die Rechte, die in der Regel zugeordneten.</param>
        <summary>
            Initialisiert eine neue Instanz der AuthorizationRuleProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rights">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessRights&gt;&gt; Rights { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.AccessRights&gt;&gt; Rights" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.AuthorizationRuleProperties.Rights" />
      <MemberSignature Language="VB.NET" Value="Public Property Rights As IList(Of Nullable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="member this.Rights : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessRights&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.AuthorizationRuleProperties.Rights" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rights")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessRights&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Berechtigungen, die in der Regel zugeordneten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.AuthorizationRuleProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="authorizationRuleProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>