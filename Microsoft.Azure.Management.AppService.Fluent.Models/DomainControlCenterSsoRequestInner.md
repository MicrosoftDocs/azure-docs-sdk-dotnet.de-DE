<Type Name="DomainControlCenterSsoRequestInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner">
  <TypeSignature Language="C#" Value="public class DomainControlCenterSsoRequestInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DomainControlCenterSsoRequestInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner" />
  <TypeSignature Language="VB.NET" Value="Public Class DomainControlCenterSsoRequestInner" />
  <TypeSignature Language="F#" Value="type DomainControlCenterSsoRequestInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Einmaliges Anmelden Anforderungsinformationen für die domänenverwaltung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainControlCenterSsoRequestInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DomainControlCenterSsoRequestInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainControlCenterSsoRequestInner (string url = null, string postParameterKey = null, string postParameterValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string url, string postParameterKey, string postParameterValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional url As String = null, Optional postParameterKey As String = null, Optional postParameterValue As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner : string * string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner (url, postParameterKey, postParameterValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="postParameterKey" Type="System.String" />
        <Parameter Name="postParameterValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="url">URL zu dem die Anforderung für einmalige Anmelden erfolgen.</param>
        <param name="postParameterKey">POST-Parameterschlüssel.</param>
        <param name="postParameterValue">POST Parameterwert an. Client sollte "Application/X-www-form-urlencoded" Codierung für diesen Wert verwenden.</param>
        <summary>
            Initialisiert eine neue Instanz der DomainControlCenterSsoRequestInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostParameterKey">
      <MemberSignature Language="C#" Value="public string PostParameterKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PostParameterKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner.PostParameterKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PostParameterKey As String" />
      <MemberSignature Language="F#" Value="member this.PostParameterKey : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner.PostParameterKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="postParameterKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft post Parameterschlüssel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostParameterValue">
      <MemberSignature Language="C#" Value="public string PostParameterValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PostParameterValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner.PostParameterValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PostParameterValue As String" />
      <MemberSignature Language="F#" Value="member this.PostParameterValue : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner.PostParameterValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="postParameterValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft post Parameterwert an. Client sollte "Application/X-www-form-urlencoded" Codierung für diesen Wert verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die URL ist, in dem die Anforderung für einmalige Anmelden erfolgen ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>