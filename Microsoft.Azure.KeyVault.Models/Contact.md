<Type Name="Contact" FullName="Microsoft.Azure.KeyVault.Models.Contact">
  <TypeSignature Language="C#" Value="public class Contact" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Contact extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.Contact" />
  <TypeSignature Language="VB.NET" Value="Public Class Contact" />
  <TypeSignature Language="F#" Value="type Contact = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Kontaktinformationen für die Zertifikate für Tresore.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Contact ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.Contact.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse wenden Sie sich an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Contact (string emailAddress = null, string name = null, string phone = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string emailAddress, string name, string phone) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.Contact.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional emailAddress As String = null, Optional name As String = null, Optional phone As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.Contact : string * string * string -&gt; Microsoft.Azure.KeyVault.Models.Contact" Usage="new Microsoft.Azure.KeyVault.Models.Contact (emailAddress, name, phone)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="emailAddress" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="phone" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="emailAddress">E-Mail-Adresse ein.</param>
        <param name="name">Name.</param>
        <param name="phone">Telefonnummer.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse wenden Sie sich an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EmailAddress">
      <MemberSignature Language="C#" Value="public string EmailAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EmailAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.Contact.EmailAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property EmailAddress As String" />
      <MemberSignature Language="F#" Value="member this.EmailAddress : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.Contact.EmailAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="email")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die e-Mail-Adresse fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.Contact.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.Contact.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt ihn fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Phone">
      <MemberSignature Language="C#" Value="public string Phone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Phone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.Contact.Phone" />
      <MemberSignature Language="VB.NET" Value="Public Property Phone As String" />
      <MemberSignature Language="F#" Value="member this.Phone : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.Contact.Phone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="phone")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Telefonnummer.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>