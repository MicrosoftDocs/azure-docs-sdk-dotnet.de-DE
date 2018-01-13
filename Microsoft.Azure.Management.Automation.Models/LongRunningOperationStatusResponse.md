<Type Name="LongRunningOperationStatusResponse" FullName="Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse">
  <TypeSignature Language="C#" Value="public class LongRunningOperationStatusResponse : Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LongRunningOperationStatusResponse extends Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class LongRunningOperationStatusResponse&#xA;Inherits AzureOperationResponse" />
  <TypeSignature Language="F#" Value="type LongRunningOperationStatusResponse = class&#xA;    inherit AzureOperationResponse" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.AzureOperationResponse</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Der Antworttext enthält den Status des angegebenen asynchronen Vorgangs, der angibt, ob es erfolgreich war, in Bearbeitung, oder fehlgeschlagen ist. Beachten Sie, dass dieser Status aus der HTTP-Statuscode zurückgegeben, die für den Get Operation Status Vorgang selbst eindeutig sind.  Wenn der asynchrone Vorgang erfolgreich war, enthält der Antworttext den HTTP-Statuscode für die erfolgreiche Anforderung.  Wenn der asynchrone Vorgang fehlgeschlagen ist, wird der Antworttext enthält den HTTP-Statuscode für die fehlerhafte Anforderung, und enthält auch Informationen zum Fehler.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LongRunningOperationStatusResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der LongRunningOperationStatusResponse-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.ErrorDetails Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse/ErrorDetails Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As LongRunningOperationStatusResponse.ErrorDetails" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.ErrorDetails with get, set" Usage="Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse+ErrorDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Wenn der asynchrone Vorgang fehlgeschlagen ist, wird der Antworttext enthält den HTTP-Statuscode für die fehlerhafte Anforderung, und enthält auch Informationen zum Fehler.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatusCode">
      <MemberSignature Language="C#" Value="public System.Net.HttpStatusCode HttpStatusCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.HttpStatusCode HttpStatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.HttpStatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpStatusCode As HttpStatusCode" />
      <MemberSignature Language="F#" Value="member this.HttpStatusCode : System.Net.HttpStatusCode with get, set" Usage="Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.HttpStatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpStatusCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Der HTTP-Statuscode für die asynchrone Anforderung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Die Anforderungs-ID der asynchronen Anforderung. Dieser Wert wird im Antwortheader von X-ms-Request-Id der asynchronen Anforderung zurückgegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.OperationStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.OperationStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As OperationStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.OperationStatus with get, set" Usage="Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.OperationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Der Status der asynchronen Anforderung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>