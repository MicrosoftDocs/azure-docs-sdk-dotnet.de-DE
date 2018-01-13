<Type Name="ProfilesOperationsExtensions" FullName="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProfilesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProfilesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProfilesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProfilesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für ProfilesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckTrafficManagerRelativeDnsNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability CheckTrafficManagerRelativeDnsNameAvailability (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability CheckTrafficManagerRelativeDnsNameAvailability(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, class Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.CheckTrafficManagerRelativeDnsNameAvailability(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckTrafficManagerRelativeDnsNameAvailability (operations As IProfilesOperations, parameters As CheckTrafficManagerRelativeDnsNameAvailabilityParameters) As TrafficManagerNameAvailability" />
      <MemberSignature Language="F#" Value="static member CheckTrafficManagerRelativeDnsNameAvailability : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters -&gt; Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.CheckTrafficManagerRelativeDnsNameAvailability (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="parameters">
            Die Traffic Manager-Name-Parameter für die CheckTrafficManagerNameAvailability zur Verfügung gestellt.
            </param>
        <summary>
            Prüft die Verfügbarkeit eines relativen Traffic Manager-DNS-Namens.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckTrafficManagerRelativeDnsNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability&gt; CheckTrafficManagerRelativeDnsNameAvailabilityAsync (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability&gt; CheckTrafficManagerRelativeDnsNameAvailabilityAsync(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, class Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.CheckTrafficManagerRelativeDnsNameAvailabilityAsync(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckTrafficManagerRelativeDnsNameAvailabilityAsync : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.CheckTrafficManagerRelativeDnsNameAvailabilityAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions/&lt;CheckTrafficManagerRelativeDnsNameAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="parameters">
            Die Traffic Manager-Name-Parameter für die CheckTrafficManagerNameAvailability zur Verfügung gestellt.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Prüft die Verfügbarkeit eines relativen Traffic Manager-DNS-Namens.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.Profile CreateOrUpdate (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, Microsoft.Azure.Management.TrafficManager.Models.Profile parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.Profile CreateOrUpdate(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, class Microsoft.Azure.Management.TrafficManager.Models.Profile parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Profile)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IProfilesOperations, resourceGroupName As String, profileName As String, parameters As Profile) As Profile" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * string * Microsoft.Azure.Management.TrafficManager.Models.Profile -&gt; Microsoft.Azure.Management.TrafficManager.Models.Profile" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, profileName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.Profile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Profile" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die Traffic Manager-Profil enthält.
            </param>
        <param name="profileName">
            Der Name des Traffic Manager-Profils.
            </param>
        <param name="parameters">
            Die Traffic Manager Profilparameter für den Vorgang CreateOrUpdate bereitgestellte.
            </param>
        <summary>
            Erstellen oder Aktualisieren eines Traffic Manager-Profils.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, Microsoft.Azure.Management.TrafficManager.Models.Profile parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, class Microsoft.Azure.Management.TrafficManager.Models.Profile parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Profile,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * string * Microsoft.Azure.Management.TrafficManager.Models.Profile * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, profileName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Profile" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die Traffic Manager-Profil enthält.
            </param>
        <param name="profileName">
            Der Name des Traffic Manager-Profils.
            </param>
        <param name="parameters">
            Die Traffic Manager Profilparameter für den Vorgang CreateOrUpdate bereitgestellte.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellen oder Aktualisieren eines Traffic Manager-Profils.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult Delete (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult Delete(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.Delete(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IProfilesOperations, resourceGroupName As String, profileName As String) As DeleteOperationResult" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * string -&gt; Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.Delete (operations, resourceGroupName, profileName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, enthält das Traffic Manager-Profil, gelöscht werden soll.
            </param>
        <param name="profileName">
            Der Name des Traffic Manager-Profil, gelöscht werden soll.
            </param>
        <summary>
            Löscht ein Traffic Manager-Profil.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt; DeleteAsync (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt; DeleteAsync(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.DeleteAsync (operations, resourceGroupName, profileName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions/&lt;DeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, enthält das Traffic Manager-Profil, gelöscht werden soll.
            </param>
        <param name="profileName">
            Der Name des Traffic Manager-Profil, gelöscht werden soll.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht ein Traffic Manager-Profil.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.Profile Get (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.Profile Get(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.Get(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProfilesOperations, resourceGroupName As String, profileName As String) As Profile" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * string -&gt; Microsoft.Azure.Management.TrafficManager.Models.Profile" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.Get (operations, resourceGroupName, profileName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.Profile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die Traffic Manager-Profil enthält.
            </param>
        <param name="profileName">
            Der Name des Traffic Manager-Profils.
            </param>
        <summary>
            Ruft eine Traffic Manager-Profil ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; GetAsync (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; GetAsync(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.GetAsync(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.GetAsync (operations, resourceGroupName, profileName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die Traffic Manager-Profil enthält.
            </param>
        <param name="profileName">
            Der Name des Traffic Manager-Profils.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Traffic Manager-Profil ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; ListAll (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; ListAll(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.ListAll(Microsoft.Azure.Management.TrafficManager.IProfilesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As IProfilesOperations) As IEnumerable(Of Profile)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.TrafficManager.IProfilesOperations -&gt; seq&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <summary>
            Listet alle Traffic Manager-Profile in einem Abonnement an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions/&lt;ListAllAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
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
            Listet alle Traffic Manager-Profile in einem Abonnement an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllInResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; ListAllInResourceGroup (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; ListAllInResourceGroup(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.ListAllInResourceGroup(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllInResourceGroup (operations As IProfilesOperations, resourceGroupName As String) As IEnumerable(Of Profile)" />
      <MemberSignature Language="F#" Value="static member ListAllInResourceGroup : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string -&gt; seq&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.ListAllInResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, enthält die Traffic Manager-Profile aufgelistet werden.
            </param>
        <summary>
            Listet alle Traffic Manager-Profile innerhalb einer Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllInResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt; ListAllInResourceGroupAsync (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt; ListAllInResourceGroupAsync(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.ListAllInResourceGroupAsync(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllInResourceGroupAsync : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.ListAllInResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions/&lt;ListAllInResourceGroupAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, enthält die Traffic Manager-Profile aufgelistet werden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle Traffic Manager-Profile innerhalb einer Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.Profile Update (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, Microsoft.Azure.Management.TrafficManager.Models.Profile parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.Profile Update(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, class Microsoft.Azure.Management.TrafficManager.Models.Profile parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.Update(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Profile)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IProfilesOperations, resourceGroupName As String, profileName As String, parameters As Profile) As Profile" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * string * Microsoft.Azure.Management.TrafficManager.Models.Profile -&gt; Microsoft.Azure.Management.TrafficManager.Models.Profile" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.Update (operations, resourceGroupName, profileName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.Profile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Profile" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die Traffic Manager-Profil enthält.
            </param>
        <param name="profileName">
            Der Name des Traffic Manager-Profils.
            </param>
        <param name="parameters">
            Die Traffic Manager Profilparameter auf den Updatevorgang angegeben.
            </param>
        <summary>
            Aktualisieren Sie ein Traffic Manager-Profil ein.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; UpdateAsync (this Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, Microsoft.Azure.Management.TrafficManager.Models.Profile parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt; UpdateAsync(class Microsoft.Azure.Management.TrafficManager.IProfilesOperations operations, string resourceGroupName, string profileName, class Microsoft.Azure.Management.TrafficManager.Models.Profile parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.TrafficManager.IProfilesOperations,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Profile,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.TrafficManager.IProfilesOperations * string * string * Microsoft.Azure.Management.TrafficManager.Models.Profile * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;" Usage="Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions.UpdateAsync (operations, resourceGroupName, profileName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.ProfilesOperationsExtensions/&lt;UpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Profile" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die Traffic Manager-Profil enthält.
            </param>
        <param name="profileName">
            Der Name des Traffic Manager-Profils.
            </param>
        <param name="parameters">
            Die Traffic Manager Profilparameter auf den Updatevorgang angegeben.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisieren Sie ein Traffic Manager-Profil ein.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>