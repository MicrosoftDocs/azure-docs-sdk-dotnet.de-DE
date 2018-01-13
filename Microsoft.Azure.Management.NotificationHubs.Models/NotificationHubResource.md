<Type Name="NotificationHubResource" FullName="Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource">
  <TypeSignature Language="C#" Value="public class NotificationHubResource : Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NotificationHubResource extends Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource" />
  <TypeSignature Language="VB.NET" Value="Public Class NotificationHubResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type NotificationHubResource = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.NotificationHubs.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die Beschreibung einer NotificationHub-Ressource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotificationHubResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der NotificationHubResource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotificationHubResource (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.NotificationHubs.Models.Sku sku = null, string notificationHubResourceName = null, string registrationTtl = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties&gt; authorizationRules = null, Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential apnsCredential = null, Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential wnsCredential = null, Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential gcmCredential = null, Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential mpnsCredential = null, Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential admCredential = null, Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential baiduCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.NotificationHubs.Models.Sku sku, string notificationHubResourceName, string registrationTtl, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties&gt; authorizationRules, class Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential apnsCredential, class Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential wnsCredential, class Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential gcmCredential, class Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential mpnsCredential, class Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential admCredential, class Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential baiduCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.NotificationHubs.Models.Sku,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties},Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential,Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential,Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential,Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential,Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential,Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.NotificationHubs.Models.Sku * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties&gt; * Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential * Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential * Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential * Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential * Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential * Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential -&gt; Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource (location, id, name, type, tags, sku, notificationHubResourceName, registrationTtl, authorizationRules, apnsCredential, wnsCredential, gcmCredential, mpnsCredential, admCredential, baiduCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.NotificationHubs.Models.Sku" />
        <Parameter Name="notificationHubResourceName" Type="System.String" />
        <Parameter Name="registrationTtl" Type="System.String" />
        <Parameter Name="authorizationRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties&gt;" />
        <Parameter Name="apnsCredential" Type="Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential" />
        <Parameter Name="wnsCredential" Type="Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential" />
        <Parameter Name="gcmCredential" Type="Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential" />
        <Parameter Name="mpnsCredential" Type="Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential" />
        <Parameter Name="admCredential" Type="Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential" />
        <Parameter Name="baiduCredential" Type="Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential" />
      </Parameters>
      <Docs>
        <param name="location">Speicherort von Ressourcen</param>
        <param name="id">Ressourcen-Id</param>
        <param name="name">Ressourcenname</param>
        <param name="type">Ressourcentyp</param>
        <param name="tags">Ressourcentags</param>
        <param name="sku">Die Sku des erstellten namespace</param>
        <param name="notificationHubResourceName">Der NotificationHub-Name.</param>
        <param name="registrationTtl">Die RegistrationTtl der erstellten NotificationHub</param>
        <param name="authorizationRules">Die AuthorizationRules der erstellten NotificationHub</param>
        <param name="apnsCredential">Die ApnsCredential der erstellten NotificationHub</param>
        <param name="wnsCredential">Die WnsCredential der erstellten NotificationHub</param>
        <param name="gcmCredential">Die GcmCredential der erstellten NotificationHub</param>
        <param name="mpnsCredential">Die MpnsCredential der erstellten NotificationHub</param>
        <param name="admCredential">Die AdmCredential der erstellten NotificationHub</param>
        <param name="baiduCredential">Die BaiduCredential der erstellten NotificationHub</param>
        <summary>
            Initialisiert eine neue Instanz der NotificationHubResource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdmCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential AdmCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential AdmCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.AdmCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property AdmCredential As AdmCredential" />
      <MemberSignature Language="F#" Value="member this.AdmCredential : Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.AdmCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.admCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die AdmCredential des erstellten NotificationHub
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApnsCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential ApnsCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential ApnsCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.ApnsCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property ApnsCredential As ApnsCredential" />
      <MemberSignature Language="F#" Value="member this.ApnsCredential : Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.ApnsCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.apnsCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ApnsCredential des erstellten NotificationHub
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties&gt; AuthorizationRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties&gt; AuthorizationRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.AuthorizationRules" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthorizationRules As IList(Of SharedAccessAuthorizationRuleProperties)" />
      <MemberSignature Language="F#" Value="member this.AuthorizationRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.AuthorizationRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authorizationRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die AuthorizationRules des erstellten NotificationHub
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaiduCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential BaiduCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential BaiduCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.BaiduCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property BaiduCredential As BaiduCredential" />
      <MemberSignature Language="F#" Value="member this.BaiduCredential : Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.BaiduCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.baiduCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die BaiduCredential des erstellten NotificationHub
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GcmCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential GcmCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential GcmCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.GcmCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property GcmCredential As GcmCredential" />
      <MemberSignature Language="F#" Value="member this.GcmCredential : Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.GcmCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gcmCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die GcmCredential des erstellten NotificationHub
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MpnsCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential MpnsCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential MpnsCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.MpnsCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property MpnsCredential As MpnsCredential" />
      <MemberSignature Language="F#" Value="member this.MpnsCredential : Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.MpnsCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.mpnsCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die MpnsCredential des erstellten NotificationHub
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationHubResourceName">
      <MemberSignature Language="C#" Value="public string NotificationHubResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NotificationHubResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.NotificationHubResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property NotificationHubResourceName As String" />
      <MemberSignature Language="F#" Value="member this.NotificationHubResourceName : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.NotificationHubResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die NotificationHub-Name.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrationTtl">
      <MemberSignature Language="C#" Value="public string RegistrationTtl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegistrationTtl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.RegistrationTtl" />
      <MemberSignature Language="VB.NET" Value="Public Property RegistrationTtl As String" />
      <MemberSignature Language="F#" Value="member this.RegistrationTtl : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.RegistrationTtl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.registrationTtl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die RegistrationTtl des erstellten NotificationHub
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WnsCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential WnsCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential WnsCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.WnsCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property WnsCredential As WnsCredential" />
      <MemberSignature Language="F#" Value="member this.WnsCredential : Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource.WnsCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.wnsCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die WnsCredential des erstellten NotificationHub
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>