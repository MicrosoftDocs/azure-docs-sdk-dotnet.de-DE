<Type Name="AzureAsyncOperationResult" FullName="Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult">
  <TypeSignature Language="C#" Value="public class AzureAsyncOperationResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureAsyncOperationResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureAsyncOperationResult" />
  <TypeSignature Language="F#" Value="type AzureAsyncOperationResult = class" />
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
            <span data-ttu-id="dfc00-101">Der Antworttext enthält den Status des angegebenen asynchronen Vorgangs, der angibt, ob er erfolgreich war, wird ausgeführt oder ist fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="dfc00-101">The response body contains the status of the specified asynchronous operation, indicating whether it has succeeded, is in progress, or has failed.</span></span> <span data-ttu-id="dfc00-102">Beachten Sie, dass dieser Status aus der HTTP-Statuscode zurückgegeben, die für den Get Operation Status Vorgang selbst eindeutig sind.</span><span class="sxs-lookup"><span data-stu-id="dfc00-102">Note that this status is distinct from the HTTP status code returned for the Get Operation Status operation itself.</span></span> <span data-ttu-id="dfc00-103">Wenn der asynchrone Vorgang erfolgreich war, enthält der Antworttext den HTTP-Statuscode für die erfolgreiche Anforderung.</span><span class="sxs-lookup"><span data-stu-id="dfc00-103">If the asynchronous operation succeeded, the response body includes the HTTP status code for the successful request.</span></span> <span data-ttu-id="dfc00-104">Wenn der asynchrone Vorgang fehlgeschlagen ist, enthält der Antworttext den HTTP-Statuscode für die fehlerhafte Anforderung und Fehler Informationen zum Fehler.</span><span class="sxs-lookup"><span data-stu-id="dfc00-104">If the asynchronous operation failed, the response body includes the HTTP status code for the failed request and error information regarding the failure.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureAsyncOperationResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dfc00-105">Initialisiert eine neue Instanz der AzureAsyncOperationResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dfc00-105">Initializes a new instance of the AzureAsyncOperationResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureAsyncOperationResult (string status = null, Microsoft.Azure.Management.Network.Fluent.Models.Error error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string status, class Microsoft.Azure.Management.Network.Fluent.Models.Error error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.#ctor(System.String,Microsoft.Azure.Management.Network.Fluent.Models.Error)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult : string * Microsoft.Azure.Management.Network.Fluent.Models.Error -&gt; Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult (status, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="error" Type="Microsoft.Azure.Management.Network.Fluent.Models.Error" />
      </Parameters>
      <Docs>
        <param name="status"><span data-ttu-id="dfc00-106">Status des Azure asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="dfc00-106">Status of the Azure async operation.</span></span> <span data-ttu-id="dfc00-107">Mögliche Werte sind: "InProgress", "Succeeded" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="dfc00-107">Possible values are: 'InProgress', 'Succeeded', and 'Failed'.</span></span> <span data-ttu-id="dfc00-108">Folgende Werte sind möglich: "InProgress", "Erfolgreich abgeschlossen", "Fehlgeschlagen"</span><span class="sxs-lookup"><span data-stu-id="dfc00-108">Possible values include: 'InProgress', 'Succeeded', 'Failed'</span></span></param>
        <param name="error">To be added.</param>
        <summary>
            <span data-ttu-id="dfc00-109">Initialisiert eine neue Instanz der AzureAsyncOperationResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dfc00-109">Initializes a new instance of the AzureAsyncOperationResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.Error Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.Error Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As Error" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.Network.Fluent.Models.Error with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.Error</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
            <span data-ttu-id="dfc00-110">Abrufen oder Festlegen des Status des Azure asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="dfc00-110">Gets or sets status of the Azure async operation.</span></span> <span data-ttu-id="dfc00-111">Mögliche Werte sind: "InProgress", "Succeeded" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="dfc00-111">Possible values are: 'InProgress', 'Succeeded', and 'Failed'.</span></span> <span data-ttu-id="dfc00-112">Folgende Werte sind möglich: "InProgress", "Erfolgreich abgeschlossen", "Fehlgeschlagen"</span><span class="sxs-lookup"><span data-stu-id="dfc00-112">Possible values include: 'InProgress', 'Succeeded', 'Failed'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>