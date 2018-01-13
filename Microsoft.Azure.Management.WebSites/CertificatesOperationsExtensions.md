<Type Name="CertificatesOperationsExtensions" FullName="Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CertificatesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CertificatesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CertificatesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CertificatesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für CertificatesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.Certificate CreateOrUpdate (this Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.Certificate certificateEnvelope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.Certificate CreateOrUpdate(class Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.Certificate certificateEnvelope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.WebSites.ICertificatesOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.Certificate)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ICertificatesOperations, resourceGroupName As String, name As String, certificateEnvelope As Certificate) As Certificate" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.WebSites.ICertificatesOperations * string * string * Microsoft.Azure.Management.WebSites.Models.Certificate -&gt; Microsoft.Azure.Management.WebSites.Models.Certificate" Usage="Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, name, certificateEnvelope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="certificateEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.Certificate" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="name">
            Der Name des Zertifikats.
            </param>
        <param name="certificateEnvelope">
            Die Details des Zertifikats, wenn sie bereits vorhanden ist.
            </param>
        <summary>
            Erstellen oder Aktualisieren eines Zertifikats.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Erstellen oder Aktualisieren eines Zertifikats.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.Certificate certificateEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.Certificate&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.Certificate certificateEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.WebSites.ICertificatesOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.Certificate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.WebSites.ICertificatesOperations * string * string * Microsoft.Azure.Management.WebSites.Models.Certificate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, name, certificateEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="certificateEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.Certificate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="name">
            Der Name des Zertifikats.
            </param>
        <param name="certificateEnvelope">
            Die Details des Zertifikats, wenn sie bereits vorhanden ist.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellen oder Aktualisieren eines Zertifikats.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Erstellen oder Aktualisieren eines Zertifikats.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.Delete(Microsoft.Azure.Management.WebSites.ICertificatesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ICertificatesOperations, resourceGroupName As String, name As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.WebSites.ICertificatesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.Delete (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="name">
            Der Name des Zertifikats.
            </param>
        <summary>
            Löschen eines Zertifikats an.
            </summary>
        <remarks>
            Löschen eines Zertifikats an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.WebSites.ICertificatesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.WebSites.ICertificatesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="name">
            Der Name des Zertifikats.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löschen eines Zertifikats an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Löschen eines Zertifikats an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.Certificate Get (this Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.Certificate Get(class Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.Get(Microsoft.Azure.Management.WebSites.ICertificatesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ICertificatesOperations, resourceGroupName As String, name As String) As Certificate" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.WebSites.ICertificatesOperations * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.Certificate" Usage="Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.Get (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="name">
            Der Name des Zertifikats.
            </param>
        <summary>
            Abrufen eines Zertifikats an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Abrufen eines Zertifikats an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt; GetAsync (this Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.Certificate&gt; GetAsync(class Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.GetAsync(Microsoft.Azure.Management.WebSites.ICertificatesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.WebSites.ICertificatesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="name">
            Der Name des Zertifikats.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Abrufen eines Zertifikats an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Abrufen eines Zertifikats an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt; List (this Microsoft.Azure.Management.WebSites.ICertificatesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Certificate&gt; List(class Microsoft.Azure.Management.WebSites.ICertificatesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.List(Microsoft.Azure.Management.WebSites.ICertificatesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ICertificatesOperations) As IPage(Of Certificate)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.WebSites.ICertificatesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ICertificatesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <summary>
            Rufen Sie aller Zertifikate für ein Abonnement an ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Rufen Sie aller Zertifikate für ein Abonnement an ab.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;&gt; ListAsync (this Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Certificate&gt;&gt; ListAsync(class Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.ListAsync(Microsoft.Azure.Management.WebSites.ICertificatesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.WebSites.ICertificatesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ICertificatesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Rufen Sie aller Zertifikate für ein Abonnement an ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Rufen Sie aller Zertifikate für ein Abonnement an ab.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt; ListByResourceGroup (this Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Certificate&gt; ListByResourceGroup(class Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.WebSites.ICertificatesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As ICertificatesOperations, resourceGroupName As String) As IPage(Of Certificate)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.WebSites.ICertificatesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <summary>
            Abrufen Sie aller Zertifikate in einer Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Abrufen Sie aller Zertifikate in einer Ressourcengruppe.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Certificate&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.WebSites.ICertificatesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.WebSites.ICertificatesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Abrufen Sie aller Zertifikate in einer Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Abrufen Sie aller Zertifikate in einer Ressourcengruppe.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Certificate&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.WebSites.ICertificatesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As ICertificatesOperations, nextPageLink As String) As IPage(Of Certificate)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.WebSites.ICertificatesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ICertificatesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Abrufen Sie aller Zertifikate in einer Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Abrufen Sie aller Zertifikate in einer Ressourcengruppe.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Certificate&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.WebSites.ICertificatesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.WebSites.ICertificatesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ICertificatesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Abrufen Sie aller Zertifikate in einer Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Abrufen Sie aller Zertifikate in einer Ressourcengruppe.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt; ListNext (this Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Certificate&gt; ListNext(class Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.ListNext(Microsoft.Azure.Management.WebSites.ICertificatesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ICertificatesOperations, nextPageLink As String) As IPage(Of Certificate)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.WebSites.ICertificatesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ICertificatesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Rufen Sie aller Zertifikate für ein Abonnement an ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Rufen Sie aller Zertifikate für ein Abonnement an ab.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Certificate&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.WebSites.ICertificatesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.WebSites.ICertificatesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions/&lt;ListNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ICertificatesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Rufen Sie aller Zertifikate für ein Abonnement an ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Rufen Sie aller Zertifikate für ein Abonnement an ab.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.Certificate Update (this Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource certificateEnvelope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.Certificate Update(class Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource certificateEnvelope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.Update(Microsoft.Azure.Management.WebSites.ICertificatesOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As ICertificatesOperations, resourceGroupName As String, name As String, certificateEnvelope As CertificatePatchResource) As Certificate" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.WebSites.ICertificatesOperations * string * string * Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource -&gt; Microsoft.Azure.Management.WebSites.Models.Certificate" Usage="Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.Update (operations, resourceGroupName, name, certificateEnvelope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="certificateEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="name">
            Der Name des Zertifikats.
            </param>
        <param name="certificateEnvelope">
            Die Details des Zertifikats, wenn sie bereits vorhanden ist.
            </param>
        <summary>
            Erstellen oder Aktualisieren eines Zertifikats.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Erstellen oder Aktualisieren eines Zertifikats.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt; UpdateAsync (this Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource certificateEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.Certificate&gt; UpdateAsync(class Microsoft.Azure.Management.WebSites.ICertificatesOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource certificateEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.WebSites.ICertificatesOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.WebSites.ICertificatesOperations * string * string * Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions.UpdateAsync (operations, resourceGroupName, name, certificateEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.CertificatesOperationsExtensions/&lt;UpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="certificateEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="name">
            Der Name des Zertifikats.
            </param>
        <param name="certificateEnvelope">
            Die Details des Zertifikats, wenn sie bereits vorhanden ist.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellen oder Aktualisieren eines Zertifikats.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Erstellen oder Aktualisieren eines Zertifikats.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>