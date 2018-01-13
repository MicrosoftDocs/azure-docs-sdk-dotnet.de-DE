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
            Der Antworttext enthält den Status des angegebenen asynchronen Vorgangs, der angibt, ob er erfolgreich war, wird ausgeführt oder ist fehlgeschlagen. Beachten Sie, dass dieser Status aus der HTTP-Statuscode zurückgegeben, die für den Get Operation Status Vorgang selbst eindeutig sind. Wenn der asynchrone Vorgang erfolgreich war, enthält der Antworttext den HTTP-Statuscode für die erfolgreiche Anforderung. Wenn der asynchrone Vorgang fehlgeschlagen ist, enthält der Antworttext den HTTP-Statuscode für die fehlerhafte Anforderung und Fehler Informationen zum Fehler.
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
            Initialisiert eine neue Instanz der AzureAsyncOperationResult-Klasse.
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
        <param name="status">Status des Azure asynchronen Vorgangs. Mögliche Werte sind: "InProgress", "Succeeded" und "Fehler". Folgende Werte sind möglich: "InProgress", "Erfolgreich abgeschlossen", "Fehlgeschlagen"</param>
        <param name="error">To be added.</param>
        <summary>
            Initialisiert eine neue Instanz der AzureAsyncOperationResult-Klasse.
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
            Abrufen oder Festlegen des Status des Azure asynchronen Vorgangs. Mögliche Werte sind: "InProgress", "Succeeded" und "Fehler". Folgende Werte sind möglich: "InProgress", "Erfolgreich abgeschlossen", "Fehlgeschlagen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>