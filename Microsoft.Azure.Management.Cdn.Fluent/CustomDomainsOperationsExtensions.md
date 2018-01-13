<Type Name="CustomDomainsOperationsExtensions" FullName="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CustomDomainsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CustomDomainsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CustomDomainsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CustomDomainsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für CustomDomainsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; BeginCreateAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; BeginCreateAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, hostName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;BeginCreateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.
            </param>
        <param name="profileName">
            Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.
            </param>
        <param name="endpointName">
            Der Name des Endpunkts unter dem Profil, das global eindeutig ist.
            </param>
        <param name="customDomainName">
            Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.
            </param>
        <param name="hostName">
            Der Hostname der benutzerdefinierten Domäne. Ein Domänenname muss sein.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt eine neue benutzerdefinierte Domäne innerhalb eines Endpunkts.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.
            </param>
        <param name="profileName">
            Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.
            </param>
        <param name="endpointName">
            Der Name des Endpunkts unter dem Profil, das global eindeutig ist.
            </param>
        <param name="customDomainName">
            Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine vorhandene benutzerdefinierte Domäne innerhalb eines Endpunkts an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; CreateAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; CreateAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.CreateAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, hostName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;CreateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.
            </param>
        <param name="profileName">
            Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.
            </param>
        <param name="endpointName">
            Der Name des Endpunkts unter dem Profil, das global eindeutig ist.
            </param>
        <param name="customDomainName">
            Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.
            </param>
        <param name="hostName">
            Der Hostname der benutzerdefinierten Domäne. Ein Domänenname muss sein.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt eine neue benutzerdefinierte Domäne innerhalb eines Endpunkts.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; DeleteAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; DeleteAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.DeleteAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.
            </param>
        <param name="profileName">
            Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.
            </param>
        <param name="endpointName">
            Der Name des Endpunkts unter dem Profil, das global eindeutig ist.
            </param>
        <param name="customDomainName">
            Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine vorhandene benutzerdefinierte Domäne innerhalb eines Endpunkts an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableCustomHttpsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; DisableCustomHttpsAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; DisableCustomHttpsAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.DisableCustomHttpsAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableCustomHttpsAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.DisableCustomHttpsAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;DisableCustomHttpsAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.
            </param>
        <param name="profileName">
            Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.
            </param>
        <param name="endpointName">
            Der Name des Endpunkts unter dem Profil, das global eindeutig ist.
            </param>
        <param name="customDomainName">
            Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Deaktivieren Sie die Https-Übermittlung der benutzerdefinierten Domäne.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableCustomHttpsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; EnableCustomHttpsAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; EnableCustomHttpsAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.EnableCustomHttpsAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableCustomHttpsAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.EnableCustomHttpsAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;EnableCustomHttpsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.
            </param>
        <param name="profileName">
            Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.
            </param>
        <param name="endpointName">
            Der Name des Endpunkts unter dem Profil, das global eindeutig ist.
            </param>
        <param name="customDomainName">
            Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Https-Übermittlung, der die benutzerdefinierte Domäne zu aktivieren.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; GetAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; GetAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.GetAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.
            </param>
        <param name="profileName">
            Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.
            </param>
        <param name="endpointName">
            Der Name des Endpunkts unter dem Profil, das global eindeutig ist.
            </param>
        <param name="customDomainName">
            Der Name der benutzerdefinierten Domäne innerhalb eines Endpunkts.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die benutzerdefinierte Domäne einer vorhandenen innerhalb eines Endpunkts ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; ListByEndpointAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; ListByEndpointAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.ListByEndpointAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByEndpointAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.ListByEndpointAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;ListByEndpointAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.
            </param>
        <param name="profileName">
            Name des CDN-Profil, das in der Ressourcengruppe eindeutig ist.
            </param>
        <param name="endpointName">
            Der Name des Endpunkts unter dem Profil, das global eindeutig ist.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller vorhandenen benutzerdefinierten Domänen innerhalb eines Endpunkts.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; ListByEndpointNextAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; ListByEndpointNextAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.ListByEndpointNextAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByEndpointNextAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.ListByEndpointNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;ListByEndpointNextAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
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
            Zeigt eine Liste aller vorhandenen benutzerdefinierten Domänen innerhalb eines Endpunkts.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>