<Type Name="ValidateResponseInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner">
  <TypeSignature Language="C#" Value="public class ValidateResponseInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ValidateResponseInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ValidateResponseInner" />
  <TypeSignature Language="F#" Value="type ValidateResponseInner = class" />
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
            Beschreibt das Ergebnis der Überprüfung der Ressource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ValidateResponseInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ValidateResponseInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ValidateResponseInner (string status = null, Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string status, class Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner.#ctor(System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional status As String = null, Optional error As ValidateResponseError = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner : string * Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner (status, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="error" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError" />
      </Parameters>
      <Docs>
        <param name="status">Ergebnis der Überprüfung.</param>
        <param name="error">Fehlerdetails für den Fall, wenn die Validierung fehlschlägt.</param>
        <summary>
            Initialisiert eine neue Instanz der ValidateResponseInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As ValidateResponseError" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert Fehlerdetails für den Fall, wenn die Validierung fehlschlägt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Ergebnis der Überprüfung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>