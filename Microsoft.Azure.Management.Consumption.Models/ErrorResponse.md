<Type Name="ErrorResponse" FullName="Microsoft.Azure.Management.Consumption.Models.ErrorResponse">
  <TypeSignature Language="C#" Value="public class ErrorResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ErrorResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Consumption.Models.ErrorResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class ErrorResponse" />
  <TypeSignature Language="F#" Value="type ErrorResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Fehlerantwort gibt an, dass der Dienst nicht die eingehende Anforderung verarbeitet werden kann. Der Grund ist in der Fehlermeldung angegeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.Models.ErrorResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse ErrorResponse an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorResponse (Microsoft.Azure.Management.Consumption.Models.ErrorDetails error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Consumption.Models.ErrorDetails error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.Models.ErrorResponse.#ctor(Microsoft.Azure.Management.Consumption.Models.ErrorDetails)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional error As ErrorDetails = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Consumption.Models.ErrorResponse : Microsoft.Azure.Management.Consumption.Models.ErrorDetails -&gt; Microsoft.Azure.Management.Consumption.Models.ErrorResponse" Usage="new Microsoft.Azure.Management.Consumption.Models.ErrorResponse error" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="error" Type="Microsoft.Azure.Management.Consumption.Models.ErrorDetails" />
      </Parameters>
      <Docs>
        <param name="error">Die Details des Fehlers.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse ErrorResponse an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Consumption.Models.ErrorDetails Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Consumption.Models.ErrorDetails Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.ErrorResponse.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As ErrorDetails" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.Consumption.Models.ErrorDetails with get, set" Usage="Microsoft.Azure.Management.Consumption.Models.ErrorResponse.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Consumption.Models.ErrorDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Details des Fehlers.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>