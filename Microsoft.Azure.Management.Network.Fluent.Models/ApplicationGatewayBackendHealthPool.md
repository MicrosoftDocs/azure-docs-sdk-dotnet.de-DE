<Type Name="ApplicationGatewayBackendHealthPool" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthPool">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayBackendHealthPool" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayBackendHealthPool extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthPool" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayBackendHealthPool" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayBackendHealthPool = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Anwendungsgateway BackendHealth Pool.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayBackendHealthPool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthPool.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ApplicationGatewayBackendHealthPool-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayBackendHealthPool (Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner backendAddressPool = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthHttpSettings&gt; backendHttpSettingsCollection = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner backendAddressPool, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthHttpSettings&gt; backendHttpSettingsCollection) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthPool.#ctor(Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthHttpSettings})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backendAddressPool As ApplicationGatewayBackendAddressPoolInner = null, Optional backendHttpSettingsCollection As IList(Of ApplicationGatewayBackendHealthHttpSettings) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthPool : Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthHttpSettings&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthPool" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthPool (backendAddressPool, backendHttpSettingsCollection)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backendAddressPool" Type="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner" />
        <Parameter Name="backendHttpSettingsCollection" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthHttpSettings&gt;" />
      </Parameters>
      <Docs>
        <param name="backendAddressPool">Verweis auf eine Ressource ApplicationGatewayBackendAddressPool.</param>
        <param name="backendHttpSettingsCollection">Liste der ApplicationGatewayBackendHealthHttpSettings Ressourcen.</param>
        <summary>
            Initialisiert eine neue Instanz der ApplicationGatewayBackendHealthPool-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendAddressPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner BackendAddressPool { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner BackendAddressPool" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthPool.BackendAddressPool" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendAddressPool As ApplicationGatewayBackendAddressPoolInner" />
      <MemberSignature Language="F#" Value="member this.BackendAddressPool : Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthPool.BackendAddressPool" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backendAddressPool")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Verweis einer ApplicationGatewayBackendAddressPool Ressource.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendHttpSettingsCollection">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthHttpSettings&gt; BackendHttpSettingsCollection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthHttpSettings&gt; BackendHttpSettingsCollection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthPool.BackendHttpSettingsCollection" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendHttpSettingsCollection As IList(Of ApplicationGatewayBackendHealthHttpSettings)" />
      <MemberSignature Language="F#" Value="member this.BackendHttpSettingsCollection : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthHttpSettings&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthPool.BackendHttpSettingsCollection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backendHttpSettingsCollection")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthHttpSettings&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der ApplicationGatewayBackendHealthHttpSettings Ressourcen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>