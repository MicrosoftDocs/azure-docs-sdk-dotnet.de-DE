<Type Name="GraphErrorException" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphErrorException">
  <TypeSignature Language="C#" Value="public class GraphErrorException : Microsoft.Rest.RestException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GraphErrorException extends Microsoft.Rest.RestException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphErrorException" />
  <TypeSignature Language="VB.NET" Value="Public Class GraphErrorException&#xA;Inherits RestException" />
  <TypeSignature Language="F#" Value="type GraphErrorException = class&#xA;    inherit RestException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.RestException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Ausnahme für eine ungültige Antwort mit GraphError Informationen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GraphErrorException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphErrorException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der GraphErrorException-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GraphErrorException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphErrorException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphErrorException : string -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphErrorException" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphErrorException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die Ausnahmemeldung.</param>
        <summary>
            Initialisiert eine neue Instanz der GraphErrorException-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GraphErrorException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphErrorException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphErrorException : string * Exception -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphErrorException" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphErrorException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">Die Ausnahmemeldung.</param>
        <param name="innerException">Beschreibung der eingeschlossenen Ausnahme.</param>
        <summary>
            Initialisiert eine neue Instanz der GraphErrorException-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphError Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphError Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphErrorException.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As GraphError" />
      <MemberSignature Language="F#" Value="member this.Body : Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphError with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphErrorException.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Body-Objekt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Request">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.HttpRequestMessageWrapper Request { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.HttpRequestMessageWrapper Request" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphErrorException.Request" />
      <MemberSignature Language="VB.NET" Value="Public Property Request As HttpRequestMessageWrapper" />
      <MemberSignature Language="F#" Value="member this.Request : Microsoft.Rest.HttpRequestMessageWrapper with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphErrorException.Request" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.HttpRequestMessageWrapper</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Informationen über die zugeordneten HTTP-Anforderung ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Response">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.HttpResponseMessageWrapper Response { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.HttpResponseMessageWrapper Response" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphErrorException.Response" />
      <MemberSignature Language="VB.NET" Value="Public Property Response As HttpResponseMessageWrapper" />
      <MemberSignature Language="F#" Value="member this.Response : Microsoft.Rest.HttpResponseMessageWrapper with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GraphErrorException.Response" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.HttpResponseMessageWrapper</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Informationen über die zugeordneten HTTP-Antwort ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>