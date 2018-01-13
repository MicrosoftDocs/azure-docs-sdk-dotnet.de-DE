<Type Name="TopLevelDomainsOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TopLevelDomainsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TopLevelDomainsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TopLevelDomainsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TopLevelDomainsOperationsExtensions = class" />
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
            Erweiterungsmethoden für TopLevelDomainsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt; GetAsync (this Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt; GetAsync(class Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.GetAsync(Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.GetAsync (operations, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="name">
            Name der Domäne der obersten Ebene.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Details zu einer Domäne auf oberster Ebene an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft Details zu einer Domäne auf oberster Ebene an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAgreementsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt; ListAgreementsAsync (this Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string name, Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainAgreementOptionInner agreementOption, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt; ListAgreementsAsync(class Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainAgreementOptionInner agreementOption, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAgreementsAsync(Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainAgreementOptionInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAgreementsAsync : Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations * string * Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainAgreementOptionInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAgreementsAsync (operations, name, agreementOption, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions/&lt;ListAgreementsAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="agreementOption" Type="Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainAgreementOptionInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="name">To be added.</param>
        <param name="agreementOption">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAgreementsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt; ListAgreementsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt; ListAgreementsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAgreementsNextAsync(Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAgreementsNextAsync : Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAgreementsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions/&lt;ListAgreementsNextAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations" RefType="this" />
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
            Ruft alle Verträge, die Benutzer muss vor dem Kauf von einer Domänenkontos akzeptieren.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft alle Verträge, die Benutzer muss vor dem Kauf von einer Domänenkontos akzeptieren.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations" RefType="this" />
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
            Rufen Sie alle Domänen auf oberster Ebene für die Registrierung unterstützt.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Rufen Sie alle Domänen auf oberster Ebene für die Registrierung unterstützt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations" RefType="this" />
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
            Rufen Sie alle Domänen auf oberster Ebene für die Registrierung unterstützt.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Rufen Sie alle Domänen auf oberster Ebene für die Registrierung unterstützt.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>