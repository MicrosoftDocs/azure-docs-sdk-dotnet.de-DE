<Type Name="CertificatesOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CertificatesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CertificatesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CertificatesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CertificatesOperationsExtensions = class" />
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
            Erweiterungsmethoden für CertificatesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner certificateEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner certificateEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, name, certificateEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="certificateEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner" />
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
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions/&lt;DeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations" RefType="this" />
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
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt; GetAsync (this Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt; GetAsync(class Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.GetAsync(Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations" RefType="this" />
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
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations" RefType="this" />
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
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations" RefType="this" />
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
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations" RefType="this" />
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
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions/&lt;ListNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations" RefType="this" />
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
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt; UpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner certificateEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt; UpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner certificateEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.UpdateAsync (operations, resourceGroupName, name, certificateEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions/&lt;UpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="certificateEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner" />
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