<Type Name="DomainAvailablilityCheckResultInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner">
  <TypeSignature Language="C#" Value="public class DomainAvailablilityCheckResultInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DomainAvailablilityCheckResultInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner" />
  <TypeSignature Language="VB.NET" Value="Public Class DomainAvailablilityCheckResultInner" />
  <TypeSignature Language="F#" Value="type DomainAvailablilityCheckResultInner = class" />
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
            Ergebnis der Domäne Verfügbarkeit.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainAvailablilityCheckResultInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DomainAvailablilityCheckResultInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainAvailablilityCheckResultInner (string name = null, Nullable&lt;bool&gt; available = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainType&gt; domainType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;bool&gt; available, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.DomainType&gt; domainType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner.#ctor(System.String,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.DomainType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional available As Nullable(Of Boolean) = null, Optional domainType As Nullable(Of DomainType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner : string * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainType&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner (name, available, domainType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="available" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="domainType" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainType&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Domäne.</param>
        <param name="available">&lt;Code&gt;"true"&lt;/code&gt; wenn Domäne werden kann, erworbenen CreateDomain-API verwenden, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <param name="domainType">Gültige Werte sind reguläre Domäne: Azure den vollen Preis von domänenregistrierung, SoftDeleted Betrag: Erwerb dieser Domäne wird einfach wiederherstellen und dieser Vorgang wird keine Kosten. Folgende Werte sind möglich: "Regular", "SoftDeleted"</param>
        <summary>
            Initialisiert eine neue Instanz der DomainAvailablilityCheckResultInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Available">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Available { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Available" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner.Available" />
      <MemberSignature Language="VB.NET" Value="Public Property Available As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Available : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner.Available" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="available")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn Domäne werden kann, erworbenen CreateDomain-API verwenden, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; /code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainType&gt; DomainType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.DomainType&gt; DomainType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner.DomainType" />
      <MemberSignature Language="VB.NET" Value="Public Property DomainType As Nullable(Of DomainType)" />
      <MemberSignature Language="F#" Value="member this.DomainType : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainType&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner.DomainType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="domainType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest gültige Werte sind reguläre Domäne: Azure den vollen Preis von domänenregistrierung, SoftDeleted Betrag: Erwerb dieser Domäne wird einfach wiederherstellen und dieser Vorgang wird keine Kosten. Folgende Werte sind möglich: "Regular", "SoftDeleted"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Domäne fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>