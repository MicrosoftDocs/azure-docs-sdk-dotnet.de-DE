<Type Name="ExternalChildResource&lt;FluentModelT,InnerModelT,IParentT,ParentImplT&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;FluentModelT,InnerModelT,IParentT,ParentImplT&gt;">
  <TypeSignature Language="C#" Value="public abstract class ExternalChildResource&lt;FluentModelT,InnerModelT,IParentT,ParentImplT&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource&lt;InnerModelT,ParentImplT,IParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;FluentModelT&gt; where FluentModelT : class, IExternalChildResource&lt;FluentModelT,IParentT&gt; where ParentImplT : IParentT" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ExternalChildResource`4&lt;class (class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource`2&lt;!FluentModelT, !IParentT&gt;) FluentModelT, InnerModelT, IParentT, (!IParentT) ParentImplT&gt; extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource`3&lt;!InnerModelT, !ParentImplT, !IParentT&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;!FluentModelT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ExternalChildResource(Of FluentModelT, InnerModelT, IParentT, ParentImplT)&#xA;Inherits ChildResource(Of InnerModelT, ParentImplT, IParentT)&#xA;Implements IRefreshable(Of FluentModelT)" />
  <TypeSignature Language="F#" Value="type ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt; = class&#xA;    inherit ChildResource&lt;'InnerModelT, #'IParentT, 'IParentT&gt;&#xA;    interface IRefreshable&lt;'FluentModelT (requires 'FluentModelT : null and 'FluentModelT :&gt; IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentModelT">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
        <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;FluentModelT,IParentT&gt;</InterfaceName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="InnerModelT" />
    <TypeParameter Name="IParentT" />
    <TypeParameter Name="ParentImplT">
      <Constraints>
        <BaseTypeName>IParentT</BaseTypeName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource&lt;InnerModelT,ParentImplT,IParentT&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="InnerT">InnerModelT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="ParentImplT">ParentImplT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="IParentT">IParentT</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;FluentModelT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="FluentModelT">die externe untergeordnete Ressource fluent-Schnittstelle</typeparam>
    <typeparam name="InnerModelT">Azure inneren Klasse Ressourcentyp, die untergeordnete Ressource darstellt.</typeparam>
    <typeparam name="IParentT">Übergeordnete fluent-Schnittstelle</typeparam>
    <typeparam name="ParentImplT">übergeordnete Implementierung Ressourcentyp</typeparam>
    <summary>
            Externalisierte untergeordnete Ressource abstrakte Implementierung.
            Um für eine Ressource externen untergeordneten berechtigt zu sein, die folgende Kriterien erfüllt werden müssen:
            1. Es ist immer eine übergeordnete Ressource zugeordnet und verfügt über keine vorhanden ist, ohne übergeordnete, d. h., wenn Sie über- und untergeordnete Ressource löschen automatisch gelöscht werden.
            2. Übergeordnete, vielleicht aber darf keine Auflistung von untergeordneten Ressourcen (d. h. als Inline-Auflistungseigenschaft).
            Es hat eine ID und können erstellt, aktualisiert, abgerufen und gelöscht werden unabhängig von der übergeordneten i.e.CRUD auf untergeordnete Ressource erfordert keine CRUD auf das übergeordnete Element (nur für interne Verwendung)
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExternalChildResource (string name, ParentImplT parent, InnerModelT innerObject);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, !ParentImplT parent, !InnerModelT innerObject) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.#ctor(System.String,`3,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, parent As ParentImplT, innerObject As InnerModelT)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt; : string * 'ParentImplT * 'InnerModelT -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt; (name, parent, innerObject)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parent" Type="ParentImplT" />
        <Parameter Name="innerObject" Type="InnerModelT" />
      </Parameters>
      <Docs>
        <param name="name">der Name des externen untergeordnete Ressource</param>
        <param name="parent">Ein Verweis auf das übergeordnete Element dieser externen untergeordnete Ressource</param>
        <param name="innerObject">Ein Verweis auf das innere Objekt, diese externen untergeordnete Ressource darstellt.</param>
        <summary>
            Erstellt eine Instanz des externen untergeordnete Ressource in-Memory.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChildResourceKey">
      <MemberSignature Language="C#" Value="public virtual string ChildResourceKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ChildResourceKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.ChildResourceKey" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property ChildResourceKey As String" />
      <MemberSignature Language="F#" Value="member this.ChildResourceKey : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;.ChildResourceKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;FluentModelT&gt; CreateAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!FluentModelT&gt; CreateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.CreateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'FluentModelT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;" Usage="externalChildResource.CreateAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;FluentModelT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Erstellt diese externen untergeordnete Ressource.
            </summary>
        <returns>der Task zum Nachverfolgen der Erstellungsaktion</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task DeleteAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.DeleteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="externalChildResource.DeleteAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Löscht diese externen untergeordnete Ressource.
            </summary>
        <returns>der Task zum Nachverfolgen der Delete-Aktion</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInnerAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;InnerModelT&gt; GetInnerAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!InnerModelT&gt; GetInnerAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.GetInnerAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetInnerAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'InnerModelT&gt;" Usage="externalChildResource.GetInnerAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;InnerModelT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public override string Name ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string Name() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.Name" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Name () As String" />
      <MemberSignature Language="F#" Value="override this.Name : unit -&gt; string" Usage="externalChildResource.Name " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PendingOperation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.PendingOperation PendingOperation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.ResourceManager.Fluent.Core.PendingOperation PendingOperation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.PendingOperation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PendingOperation As PendingOperation" />
      <MemberSignature Language="F#" Value="member this.PendingOperation : Microsoft.Azure.Management.ResourceManager.Fluent.Core.PendingOperation" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;.PendingOperation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.PendingOperation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>die im Speicher enthaltenen Status dieses untergeordnete Ressource und der Status steht für alle Ausstehende Aktion auf die untergeordnete Ressource.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public virtual FluentModelT Refresh ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !FluentModelT Refresh() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.Refresh" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Refresh () As FluentModelT" />
      <MemberSignature Language="F#" Value="abstract member Refresh : unit -&gt; 'FluentModelT&#xA;override this.Refresh : unit -&gt; 'FluentModelT" Usage="externalChildResource.Refresh " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1.Refresh</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>FluentModelT</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;FluentModelT&gt; RefreshAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!FluentModelT&gt; RefreshAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.RefreshAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'FluentModelT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;&#xA;override this.RefreshAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'FluentModelT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;" Usage="externalChildResource.RefreshAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1.RefreshAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4/&lt;RefreshAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;FluentModelT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;FluentModelT&gt; UpdateAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!FluentModelT&gt; UpdateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.UpdateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'FluentModelT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;" Usage="externalChildResource.UpdateAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;FluentModelT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Aktualisiert diese externen untergeordnete Ressource.
            </summary>
        <returns>der Task zum Nachverfolgen der Update-Aktion</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>