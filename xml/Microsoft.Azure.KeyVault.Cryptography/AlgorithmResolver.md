<Type Name="AlgorithmResolver" FullName="Microsoft.Azure.KeyVault.Cryptography.AlgorithmResolver">
  <TypeSignature Language="C#" Value="public class AlgorithmResolver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi AlgorithmResolver extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Cryptography.AlgorithmResolver" />
  <TypeSignature Language="VB.NET" Value="Public Class AlgorithmResolver" />
  <TypeSignature Language="F#" Value="type AlgorithmResolver = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="364b2-101">Wird der Name des Algorithmus zu Implementierungen aufgelöst.</span><span class="sxs-lookup"><span data-stu-id="364b2-101">Resolves algorithm name to implementations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AlgorithmResolver ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.AlgorithmResolver.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAlgorithm">
      <MemberSignature Language="C#" Value="public void AddAlgorithm (string algorithmName, Microsoft.Azure.KeyVault.Cryptography.Algorithm provider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddAlgorithm(string algorithmName, class Microsoft.Azure.KeyVault.Cryptography.Algorithm provider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.AlgorithmResolver.AddAlgorithm(System.String,Microsoft.Azure.KeyVault.Cryptography.Algorithm)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddAlgorithm (algorithmName As String, provider As Algorithm)" />
      <MemberSignature Language="F#" Value="member this.AddAlgorithm : string * Microsoft.Azure.KeyVault.Cryptography.Algorithm -&gt; unit" Usage="algorithmResolver.AddAlgorithm (algorithmName, provider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="algorithmName" Type="System.String" />
        <Parameter Name="provider" Type="Microsoft.Azure.KeyVault.Cryptography.Algorithm" />
      </Parameters>
      <Docs>
        <param name="algorithmName"><span data-ttu-id="364b2-102">Der Name des Algorithmus</span><span class="sxs-lookup"><span data-stu-id="364b2-102">The algorithm name</span></span></param>
        <param name="provider"><span data-ttu-id="364b2-103">Der Anbieter für den Algorithmus</span><span class="sxs-lookup"><span data-stu-id="364b2-103">The provider for the algorithm</span></span></param>
        <summary>
            <span data-ttu-id="364b2-104">Fügt einen Algorithmus für den Konfliktlöser</span><span class="sxs-lookup"><span data-stu-id="364b2-104">Adds an algorithm to the resolver</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.KeyVault.Cryptography.AlgorithmResolver Default;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.KeyVault.Cryptography.AlgorithmResolver Default" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.KeyVault.Cryptography.AlgorithmResolver.Default" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Default As AlgorithmResolver " />
      <MemberSignature Language="F#" Value=" staticval mutable Default : Microsoft.Azure.KeyVault.Cryptography.AlgorithmResolver" Usage="Microsoft.Azure.KeyVault.Cryptography.AlgorithmResolver.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Cryptography.AlgorithmResolver</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Cryptography.Algorithm this[string algorithmName] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Cryptography.Algorithm Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Cryptography.AlgorithmResolver.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(algorithmName As String) As Algorithm" />
      <MemberSignature Language="F#" Value="member this.Item(string) : Microsoft.Azure.KeyVault.Cryptography.Algorithm with get, set" Usage="Microsoft.Azure.KeyVault.Cryptography.AlgorithmResolver.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Cryptography.Algorithm</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="algorithmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="algorithmName"><span data-ttu-id="364b2-105">Der Name des Algorithmus</span><span class="sxs-lookup"><span data-stu-id="364b2-105">The algorithm name</span></span></param>
        <summary>
            <span data-ttu-id="364b2-106">Gibt die Implementierung für einen Algorithmusnamen zurück</span><span class="sxs-lookup"><span data-stu-id="364b2-106">Returns the implementation for an algorithm name</span></span>
            </summary>
        <value />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAlgorithm">
      <MemberSignature Language="C#" Value="public void RemoveAlgorithm (string algorithmName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveAlgorithm(string algorithmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.AlgorithmResolver.RemoveAlgorithm(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAlgorithm (algorithmName As String)" />
      <MemberSignature Language="F#" Value="member this.RemoveAlgorithm : string -&gt; unit" Usage="algorithmResolver.RemoveAlgorithm algorithmName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="algorithmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="algorithmName"><span data-ttu-id="364b2-107">Der Name des Algorithmus</span><span class="sxs-lookup"><span data-stu-id="364b2-107">The algorithm name</span></span></param>
        <summary>
            <span data-ttu-id="364b2-108">Entfernt einen Algorithmus aus der Konfliktlöser</span><span class="sxs-lookup"><span data-stu-id="364b2-108">Removes an algorithm from the resolver</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>