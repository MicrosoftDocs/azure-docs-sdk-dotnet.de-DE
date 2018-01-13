<Type Name="ApplicationGatewayBackendHealthHttpSettings" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayBackendHealthHttpSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayBackendHealthHttpSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayBackendHealthHttpSettings" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayBackendHealthHttpSettings = class" />
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
            Application Gateway BackendHealthHttp Einstellungen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayBackendHealthHttpSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings.#ctor" />
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
            Initialisiert eine neue Instanz der ApplicationGatewayBackendHealthHttpSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayBackendHealthHttpSettings (Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings backendHttpSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer&gt; servers = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings backendHttpSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer&gt; servers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings.#ctor(Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backendHttpSettings As ApplicationGatewayBackendHttpSettings = null, Optional servers As IList(Of ApplicationGatewayBackendHealthServer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings : Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer&gt; -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings (backendHttpSettings, servers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backendHttpSettings" Type="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings" />
        <Parameter Name="servers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer&gt;" />
      </Parameters>
      <Docs>
        <param name="backendHttpSettings">Verweis auf eine Ressource ApplicationGatewayBackendHttpSettings.</param>
        <param name="servers">Liste der ApplicationGatewayBackendHealthServer Ressourcen.</param>
        <summary>
            Initialisiert eine neue Instanz der ApplicationGatewayBackendHealthHttpSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendHttpSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings BackendHttpSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings BackendHttpSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings.BackendHttpSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendHttpSettings As ApplicationGatewayBackendHttpSettings" />
      <MemberSignature Language="F#" Value="member this.BackendHttpSettings : Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings.BackendHttpSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backendHttpSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Verweis einer ApplicationGatewayBackendHttpSettings Ressource.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Servers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer&gt; Servers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer&gt; Servers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings.Servers" />
      <MemberSignature Language="VB.NET" Value="Public Property Servers As IList(Of ApplicationGatewayBackendHealthServer)" />
      <MemberSignature Language="F#" Value="member this.Servers : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings.Servers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="servers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der ApplicationGatewayBackendHealthServer Ressourcen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthHttpSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationGatewayBackendHealthHttpSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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