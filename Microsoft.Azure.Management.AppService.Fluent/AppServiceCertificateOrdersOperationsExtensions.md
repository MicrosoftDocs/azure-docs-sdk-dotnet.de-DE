<Type Name="AppServiceCertificateOrdersOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AppServiceCertificateOrdersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AppServiceCertificateOrdersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AppServiceCertificateOrdersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AppServiceCertificateOrdersOperationsExtensions = class" />
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
            Erweiterungsmethoden für AppServiceCertificateOrdersOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner certificateDistinguishedName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner certificateDistinguishedName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, certificateOrderName, certificateDistinguishedName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="certificateDistinguishedName" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="certificateOrderName">
            Der Name des Auftrags Zertifikat.
            </param>
        <param name="certificateDistinguishedName">
            Distinguished Name, um für die Bestellung Zertifikat verwenden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellen Sie oder aktualisieren Sie ein Zertifikat PurchaseOrder-Objekt.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Erstellen Sie oder aktualisieren Sie ein Zertifikat PurchaseOrder-Objekt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; BeginCreateOrUpdateCertificateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner keyVaultCertificate, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; BeginCreateOrUpdateCertificateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner keyVaultCertificate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateCertificateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateCertificateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateCertificateAsync (operations, resourceGroupName, certificateOrderName, name, keyVaultCertificate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;BeginCreateOrUpdateCertificateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyVaultCertificate" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="certificateOrderName">
            Der Name des Auftrags Zertifikat.
            </param>
        <param name="name">
            Der Name des Zertifikats.
            </param>
        <param name="keyVaultCertificate">
            Ressourcen-ID für Key Vault-Zertifikat
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert ein Zertifikat, und ordnet schlüsseltresor geheime Schlüssel.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Erstellt oder aktualisiert ein Zertifikat, und ordnet schlüsseltresor geheime Schlüssel.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner certificateDistinguishedName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner certificateDistinguishedName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, certificateOrderName, certificateDistinguishedName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="certificateDistinguishedName" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="certificateOrderName">
            Der Name des Auftrags Zertifikat.
            </param>
        <param name="certificateDistinguishedName">
            Distinguished Name, um für die Bestellung Zertifikat verwenden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellen Sie oder aktualisieren Sie ein Zertifikat PurchaseOrder-Objekt.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Erstellen Sie oder aktualisieren Sie ein Zertifikat PurchaseOrder-Objekt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; CreateOrUpdateCertificateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner keyVaultCertificate, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; CreateOrUpdateCertificateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner keyVaultCertificate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateCertificateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateCertificateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateCertificateAsync (operations, resourceGroupName, certificateOrderName, name, keyVaultCertificate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;CreateOrUpdateCertificateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyVaultCertificate" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="certificateOrderName">
            Der Name des Auftrags Zertifikat.
            </param>
        <param name="name">
            Der Name des Zertifikats.
            </param>
        <param name="keyVaultCertificate">
            Ressourcen-ID für Key Vault-Zertifikat
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert ein Zertifikat, und ordnet schlüsseltresor geheime Schlüssel.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Erstellt oder aktualisiert ein Zertifikat, und ordnet schlüsseltresor geheime Schlüssel.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.DeleteAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="certificateOrderName">
            Der Name des Auftrags Zertifikat.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löschen eines vorhandenen Zertifikats-Auftrags an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Löschen eines vorhandenen Zertifikats-Auftrags an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteCertificateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteCertificateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.DeleteCertificateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCertificateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.DeleteCertificateAsync (operations, resourceGroupName, certificateOrderName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;DeleteCertificateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
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
        <param name="certificateOrderName">
            Der Name des Auftrags Zertifikat.
            </param>
        <param name="name">
            Der Name des Zertifikats.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löschen Sie das Zertifikat mit einem Zertifikat zugeordnet ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Löschen Sie das Zertifikat mit einem Zertifikat zugeordnet ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; GetAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; GetAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.GetAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.GetAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="certificateOrderName">
            Der Name des Auftrags Zertifikat...
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Abrufen einer zertifikatreihenfolge an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Abrufen einer zertifikatreihenfolge an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; GetCertificateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; GetCertificateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.GetCertificateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.GetCertificateAsync (operations, resourceGroupName, certificateOrderName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;GetCertificateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
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
        <param name="certificateOrderName">
            Der Name des Auftrags Zertifikat.
            </param>
        <param name="name">
            Der Name des Zertifikats.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Abrufen einer zertifikatreihenfolge zugeordneten Zertifikats.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Abrufen einer zertifikatreihenfolge zugeordneten Zertifikats.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
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
            Listen Sie aller Zertifikat Bestellungen in einem Abonnement an auf.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller Zertifikat Bestellungen in einem Abonnement an auf.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
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
            Abrufen von Zertifikat Aufträge in einer Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Abrufen von Zertifikat Aufträge in einer Ressourcengruppe.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
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
            Abrufen von Zertifikat Aufträge in einer Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Abrufen von Zertifikat Aufträge in einer Ressourcengruppe.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCertificatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt; ListCertificatesAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt; ListCertificatesAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCertificatesAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListCertificatesAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="certificateOrderName">
            Der Name des Auftrags Zertifikat.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listen Sie alle zugeordneten Zertifikate für eine zertifikatreihenfolge.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie alle zugeordneten Zertifikate für eine zertifikatreihenfolge.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCertificatesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt; ListCertificatesNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt; ListCertificatesNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCertificatesNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListCertificatesNextAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
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
            Listen Sie alle zugeordneten Zertifikate für eine zertifikatreihenfolge.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie alle zugeordneten Zertifikate für eine zertifikatreihenfolge.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListNextAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
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
            Listen Sie aller Zertifikat Bestellungen in einem Abonnement an auf.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller Zertifikat Bestellungen in einem Abonnement an auf.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReissueAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ReissueAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.ReissueCertificateOrderRequestInner reissueCertificateOrderRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ReissueAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.ReissueCertificateOrderRequestInner reissueCertificateOrderRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ReissueAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ReissueCertificateOrderRequestInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReissueAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.ReissueCertificateOrderRequestInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ReissueAsync (operations, resourceGroupName, certificateOrderName, reissueCertificateOrderRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ReissueAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="reissueCertificateOrderRequest" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ReissueCertificateOrderRequestInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="certificateOrderName">
            Der Name des Auftrags Zertifikat.
            </param>
        <param name="reissueCertificateOrderRequest">
            Parameter für die Aktualisierung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Geben Sie eine vorhandene zertifikatreihenfolge erneut aus.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Geben Sie eine vorhandene zertifikatreihenfolge erneut aus.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RenewAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.RenewCertificateOrderRequestInner renewCertificateOrderRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RenewAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.RenewCertificateOrderRequestInner renewCertificateOrderRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RenewAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.RenewCertificateOrderRequestInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RenewAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.RenewCertificateOrderRequestInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RenewAsync (operations, resourceGroupName, certificateOrderName, renewCertificateOrderRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;RenewAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="renewCertificateOrderRequest" Type="Microsoft.Azure.Management.AppService.Fluent.Models.RenewCertificateOrderRequestInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="certificateOrderName">
            Der Name des Auftrags Zertifikat.
            </param>
        <param name="renewCertificateOrderRequest">
            Erneuern von Parametern
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erneuern eines vorhandenen Zertifikats-Auftrags an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Erneuern eines vorhandenen Zertifikats-Auftrags an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResendEmailAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResendEmailAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResendEmailAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ResendEmailAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResendEmailAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ResendEmailAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ResendEmailAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="certificateOrderName">
            Der Name des Auftrags Zertifikat.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Senden Sie Zertifikat e-Mail erneut.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Senden Sie Zertifikat e-Mail erneut.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResendRequestEmailsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResendRequestEmailsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner nameIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResendRequestEmailsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner nameIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ResendRequestEmailsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResendRequestEmailsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ResendRequestEmailsAsync (operations, resourceGroupName, certificateOrderName, nameIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ResendRequestEmailsAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="nameIdentifier" Type="Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="certificateOrderName">To be added.</param>
        <param name="nameIdentifier">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveCertificateActionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner&gt;&gt; RetrieveCertificateActionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner&gt;&gt; RetrieveCertificateActionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateActionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RetrieveCertificateActionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateActionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;RetrieveCertificateActionsAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
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
            Der Name des Auftrags Zertifikat.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Die Liste der Aktionen Zertifikat abrufen.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Die Liste der Aktionen Zertifikat abrufen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveCertificateEmailHistoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateEmailInner&gt;&gt; RetrieveCertificateEmailHistoryAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateEmailInner&gt;&gt; RetrieveCertificateEmailHistoryAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateEmailHistoryAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RetrieveCertificateEmailHistoryAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateEmailInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateEmailHistoryAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;RetrieveCertificateEmailHistoryAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateEmailInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
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
            Der Name des Auftrags Zertifikat.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Abgerufen Sie e-Mail-Verlauf werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Abgerufen Sie e-Mail-Verlauf werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveSiteSealAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealInner&gt; RetrieveSiteSealAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealRequestInner siteSealRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealInner&gt; RetrieveSiteSealAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealRequestInner siteSealRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveSiteSealAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealRequestInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RetrieveSiteSealAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealRequestInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveSiteSealAsync (operations, resourceGroupName, certificateOrderName, siteSealRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;RetrieveSiteSealAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="siteSealRequest" Type="Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealRequestInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="certificateOrderName">
            Der Name des Auftrags Zertifikat.
            </param>
        <param name="siteSealRequest">
            Standort versiegeln-Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Domänenbesitz für diesen Auftrag Zertifikat.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Domänenbesitz für diesen Auftrag Zertifikat.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidatePurchaseInformationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ValidatePurchaseInformationAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner appServiceCertificateOrder, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ValidatePurchaseInformationAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner appServiceCertificateOrder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ValidatePurchaseInformationAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ValidatePurchaseInformationAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ValidatePurchaseInformationAsync (operations, appServiceCertificateOrder, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ValidatePurchaseInformationAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="appServiceCertificateOrder" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="appServiceCertificateOrder">
            Informationen für eine Bestellung Zertifikat.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Für eine Bestellung Zertifikat zu überprüfen.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Für eine Bestellung Zertifikat zu überprüfen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnershipAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task VerifyDomainOwnershipAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task VerifyDomainOwnershipAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.VerifyDomainOwnershipAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyDomainOwnershipAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.VerifyDomainOwnershipAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;VerifyDomainOwnershipAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="certificateOrderName">
            Der Name des Auftrags Zertifikat.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Domänenbesitz für diesen Auftrag Zertifikat.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Domänenbesitz für diesen Auftrag Zertifikat.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>